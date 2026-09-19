# Piano Teacher Website

A responsive, static portfolio and business website for **Larysa Robinson**, a piano teacher serving students in the West Palmdale and Quartz Hill areas of California. The site presents private piano lessons, teaching experience, studio media, reviews, and contact information for in-person and online inquiries.

## Features

- Responsive desktop and mobile navigation
- Hero image slider with automatic rotation and touch/swipe support
- Sections for:
  - About the teacher
  - Piano lessons and music theory
  - Beginner instruction and performance preparation
  - Studio gallery
  - Student reviews
  - Contact information and inquiry form
- Dedicated photo gallery page with:
  - Full-screen modal viewer
  - Previous/next navigation
  - Thumbnail navigation
  - Touch/swipe support
- Embedded performance videos from YouTube
- Scroll-triggered content animations using `IntersectionObserver`
- Smooth back-to-top control
- Accessible labels, buttons, landmarks, and responsive navigation controls
- Contact form submission through Formspree

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Formspree for contact form delivery
- YouTube embeds for video content

## Project Structure

```text
.
├── index.html              # Main landing page
├── photo_gallery.html      # Photo gallery and videos page
├── styles.css              # Site layout, styling, and responsive rules
├── script.js               # Sliders, navigation, gallery modal, form, and animations
├── favicon.png             # Browser favicon
└── assets/
    ├── fonts/              # Local font assets
    ├── images/             # General image assets
    └── images_mom/         # Hero and gallery images
```

## Run Locally

This project does not require a build step or package manager.

### Option 1: Open directly

Open `index.html` in a modern web browser.

### Option 2: Use a local server

Using Python:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

Using Node.js and `npx`:

```bash
npx serve .
```

A local server is recommended because it provides behavior closer to a deployed website and avoids restrictions that can affect local file URLs.

## Customization

- Update page content and contact details in `index.html`.
- Add or replace gallery images in `assets/images_mom/` and update their references in `index.html` and `photo_gallery.html`.
- Edit colors, typography, layout, and breakpoints in `styles.css`.
- Adjust slider timing and interactive behavior in `script.js`.
- Replace the Formspree endpoint in the contact form if the site is connected to a different account or form.
- Replace placeholder review text and video card labels before production use.
- Update canonical URLs in both HTML pages when the final production domain is known.

## Deployment

Because this is a static website, it can be deployed to any static hosting provider, including:

- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any standard web server

For GitHub Pages, publish the repository from the branch containing `index.html`. Ensure that asset paths remain relative to the project root.

## Contact Form

The inquiry form currently submits to Formspree through the endpoint configured in `index.html`. To use the form in production:

1. Create or select a Formspree form.
2. Replace the form `action` URL with the endpoint provided by Formspree.
3. Submit a test inquiry after deployment.
4. Confirm that the success and error states behave as expected.

## License

No license has been specified for this repository. Unless a license is added, all original website content and assets should be treated as reserved by their respective owners.
