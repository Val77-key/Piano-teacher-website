
# Larysa Robinson | Piano Teacher & Music Educator

A responsive website for piano teacher and music educator Larysa Robinson**, designed to present her teaching experience, educational background, services, media, testimonials, and contact information.

This project is also my first portfolio project, built from scratch using vanilla HTML, CSS, and JavaScript.

## Live Website

[ live website URL here]

## Overview

The website provides prospective students and families with information about Larysa's teaching approach, qualifications, lessons, and experience.

The design focuses on a warm, elegant visual style while remaining responsive and accessible across desktop, tablet, and mobile devices.

## Features

- Responsive design for desktop, tablet, and mobile
- Hero image carousel with:
  - Previous/next controls
  - Automatic slide changes
  - Animated slide content
- Responsive navigation
- Mobile navigation menu
- About section with teacher information and educational background
- Piano and music theory lesson information
- Personalized lesson descriptions
- Performance preparation information
- Image gallery
- Full-screen image modal
- Touch/pointer interaction for the gallery
- Video gallery
- Testimonials/reviews carousel
- Contact form
- Form submission through Formspree
- Back-to-top button
- CSS animations and transitions
- Dark-themed form section
- Responsive typography and layouts
- Optimized WebP images
- Semantic HTML structure
- Accessibility considerations including:
  - Appropriate semantic elements
  - Button elements for interactive controls
  - aria-live for dynamic content
  - Keyboard/focus considerations
  - Dialog-based image viewing

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

JavaScript is used to provide interactive functionality throughout the website.

### Hero Carousel

The homepage includes an image carousel with manual navigation and automatic slide changes.

The carousel keeps track of the current slide and dynamically changes which slide is displayed.

It also resets CSS animation classes so that the text animation can play again when a slide becomes active.

### Mobile Navigation

The mobile navigation menu is controlled with JavaScript and CSS transitions.

The menu can be opened and closed without relying on inline HTML event handlers.

### Image Gallery

The gallery uses JavaScript to open images in a modal view.

Pointer events are also used to support swipe-style interaction on touch devices.

### Reviews Carousel

Testimonials are displayed using a rotating carousel that automatically changes the visible review.

### Back-to-Top Button

The back-to-top button appears after the user scrolls down the page and allows the user to return to the top smoothly.

### Scroll-Based Animations

IntersectionObserver is used to trigger animations when selected sections enter the viewport.

## Responsive Design

The website was designed and tested across different screen sizes, including mobile devices, tablets, and desktop screens.

Particular attention was given to:

- Small mobile screens
- iPhone layouts
- Navigation behavior
- Image cropping
- Hero section height
- Touch interactions
- Modal scrolling
- Responsive typography
- Desktop/mobile layout changes

## Accessibility

Accessibility was considered throughout the project.

Examples include:

- Semantic HTML elements
- Descriptive image alt attributes
- Buttons for interactive controls
- Visible focus states
- aria-live for changing carousel/review content
- Keyboard-friendly interactive elements
- Dialog element for the image modal

## Image Optimization

Large source images were cropped and resized before being used on the website.

Images are served in modern **WebP** format where appropriate to reduce file size and improve page loading performance.

Explicit image dimensions are also provided where appropriate to help the browser determine image layout before the images finish loading.

## Contact Form

The contact form allows visitors to submit:

- Name
- Email
- Message

Form submissions are handled through Formspree, so the website does not require its own backend server for contact messages.

## Design

The visual design uses a warm, elegant aesthetic inspired by the subject of classical piano and music education.

The project uses custom fonts, CSS variables, responsive layouts, image overlays, gradients, animations, and carefully selected colors to create a consistent visual identity.

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
