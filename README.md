# Lesotho Tourism website

A responsive five-page student project for the Principles of Web Design assignment. It demonstrates HTML5 semantic elements, an external custom stylesheet, Bootstrap 5, JavaScript gallery controls, and validated trip enquiry and registration forms.

## Pages

- `index.html` — home and destination highlights
- `about.html` — Lesotho and responsible travel
- `experiences.html` — destinations, accommodation and activities
- `gallery.html` — image gallery with a Bootstrap modal lightbox
- `contact.html` — trip enquiry and registration forms

## Folder structure

```text
lesotho-tourism/
├── index.html
├── about.html
├── experiences.html
├── gallery.html
├── contact.html
├── README.md
└── assets/
    ├── css/styles.css
    ├── js/main.js
    └── images/                 (available for local images)
```

The site uses Bootstrap 5.3.3 and Google Fonts from their public CDNs. Photographs are loaded from Unsplash, so an internet connection is needed for those images and the framework. The image-credit note on the gallery explains that these are illustrative images and may not show the named places.

## Run locally

1. Open the `lesotho-tourism` folder.
2. Double-click `index.html` to view it in a browser. For a local web server, open a terminal in this folder and run `py -m http.server 8000` (or `python -m http.server 8000`), then visit `http://localhost:8000`.
3. Use the navbar to move between pages. On the Contact page, try both form tabs. The forms validate in the browser and display a demo success message; they do not transmit or save personal details.

## Host or publish

Upload the complete `lesotho-tourism` folder to a static host such as GitHub Pages, Netlify or a school web server. Keep all five HTML pages and the `assets` directory together so their relative links continue to work. This project has not been deployed or published to GitHub.

## Assignment features included

- Five interconnected pages with headings, navigation, lists/content sections, images with alternative text, and forms.
- Custom typography, colour palette, layout, hover states, transitions, cards, and responsive breakpoints in `assets/css/styles.css`.
- Bootstrap navbar, grid, cards, accordion, badge, alert, form controls, buttons and modal.
- Gallery image selection, lightbox preview, next/previous controls, image count and left/right keyboard controls.
- Trip enquiry validation for name, email, telephone and required fields.
- Traveller registration for name, email, telephone, optional gender, password, confirmation and terms acknowledgement. Password validation requires eight or more characters with at least one letter and one number.

## Customizing

Replace the Unsplash image URLs in the HTML and stylesheet with images you have permission to use. Put local images in `assets/images/` and update each `src` or CSS `background-image` to a relative path. If you connect a real booking service later, add a secure server endpoint; the current browser-only forms are demonstrations.
