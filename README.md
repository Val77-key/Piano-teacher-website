
# Larysa Robinson | Piano Teacher & Music Educator

A responsive, multi-page website for Larysa Robinson, a piano teacher and music educator. The site introduces her teaching approach, presents lesson-related information, shares student and parent reviews, and gives prospective students a clear way to get in touch.

This project was built with semantic HTML, custom CSS, and vanilla JavaScript. It focuses on a warm, polished visual identity, responsive layouts, and small interactions that make the site easy to explore on both desktop and mobile devices.

This project is also my first portfolio project, built from scratch using vanilla HTML, CSS, and JavaScript.

## Live Website

https://www.larysarobinsonpiano.com/

## Source code

github.com/Val77-key/Piano-teacher-website

## Overview

The website provides prospective students and families with information about Larysa's teaching approach, qualifications, lessons, and experience.

The design focuses on a warm, elegant visual style while remaining responsive and accessible across desktop, tablet, and mobile devices.

## Features

- Responsive desktop and mobile layouts
- Separate desktop and mobile navigation
- Mobile menu that opens, closes, and closes after a navigation link is selected
- Hero image slider that advances automatically every six seconds
- Swipe support for the hero slider
- Active navigation states based on the current page or section
- Smooth back-to-top control
- Main-page sections for Larysa's background, teaching role, services, gallery, reviews, and contact information
- Dedicated photo-gallery page with an image modal
- Gallery modal controls, thumbnail selection, outside-click closing, and swipe navigation
- Automatically rotating student and parent reviews
- Contact form submission feedback
- Scroll-triggered content-reveal animations

## Technologies

- **HTML5**
- **CSS3**
- **JavaScript (ES6+)**
- **Formspree** — contact form handling
- **Git & GitHub** — version control and project hosting
- **GitHub Pages** — deployment

## Project Structure

text
piano-teacher-website/
│
├── index.html
├── photo_gallery.html
├── styles.css
├── script.js
│
├── assets/
│   ├── images_mom/
│   │   └── ...
│   │
│   └── ...
│
└── README.md


## JavaScript Functionality

The JavaScript file adds the site's interactive behavior while checking that optional page elements exist before using them. This allows shared code to run on pages that do not contain every feature.

### Navigation

- Opens and closes the mobile navigation menu
- Applies an 'active' class to desktop and mobile links for the current page or hash-linked section
- Updates active navigation links when the URL hash changes

### Sliders and carousels

- The hero slider cycles through slides every six seconds
- Hero slides can also be changed with horizontal swipe gestures
- The reviews track moves horizontally and rotates through four review panels every seven seconds

### Gallery modal

- Opens the selected gallery image in a modal
- Keeps the selected modal slide and thumbnail in sync
- Supports previous/next controls and horizontal swiping
- Closes from the close control or when the backdrop is selected
- Adds a touch-specific visual state to gallery controls

### Contact form

The form submission is handled asynchronously with 'fetch()':

1. Prevents the browser's default form submission.
2. Disables the submit button while the request is in progress.
3. Sends the form data to the form's configured 'action' URL.
4. Resets and hides the form after a successful response, then shows a success message.
5. Re-enables the button and alerts the visitor if the request cannot be sent.

### Scroll effects

'IntersectionObserver' is used to add an 'appears' class as sections enter the viewport. This supports reveal animations without continuously running animation logic during scrolling.

## Design Notes

The visual system uses locally hosted web fonts and CSS custom properties for reusable colors. Typography combines:

- **Playfair Display** for expressive display typography
- **DM Sans** for clear interface and body copy
- **EB Garamond** for a more literary serif accent

The CSS also includes a dark-color preference through 'prefers-color-scheme', allowing core color variables to adapt to a visitor's system setting.

## Responsive and Accessibility Considerations

- Desktop and mobile navigation are provided as separate experiences.
- Pointer events support mouse, touch, and pen interactions for slider and gallery gestures.
- Images include alternative text and explicit dimensions.
- Sections use labels to make their purpose clearer to assistive technology.
- Decorative quotation marks are hidden from assistive technology.
- Modal thumbnails receive focus when selected, helping keep the current gallery item clear for keyboard users.
- Local fonts use 'font-display: swap' so text remains visible while fonts load.


## What I Learned

This project was built as an opportunity to apply and strengthen my frontend development skills.

Through the project I practiced:

- Semantic HTML
- CSS layout and responsive design
- CSS variables
- Flexbox and Grid
- CSS animations and transitions
- Responsive navigation
- DOM manipulation
- Event listeners
- JavaScript functions and state
- Array/NodeList manipulation
- Intersection Observer API
- Pointer Events API
- Modal/dialog behavior
- Form handling
- Fetch/API concepts
- Image optimization
- WebP conversion
- Accessibility
- Git and GitHub
- Deployment

## Future Improvements

Possible future improvements include:

- Adding more advanced image optimization with responsive image sources
- Further improving accessibility
- Adding additional performance optimizations
- Improving content management so the site owner can update content without editing source code
- Migrating to a component-based framework such as React as a future learning project

## Credits

**Website:** Larysa Robinson | Piano Teacher & Music Educator

**Developer:** Valentyn Kisilenko

Built as a personal frontend portfolio project using vanilla HTML, CSS, and JavaScript.

© 2026 Larysa Robinson
