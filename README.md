# AI-PR Empowerment Series Website

## Overview
This is the official website for the **AI-PR Empowerment Series**, a 9-month training program by Toastmasters District 106, led by Public Relations Manager Leo Smith. The series equips Toastmasters with AI tools to enhance public relations, club visibility, and member recruitment. The website promotes the series, provides session details, and includes a registration form.

## Features
- **Responsive Design**: Optimized for mobile and desktop using a viewport meta tag and modern CSS (via `styles.css`).
- **Navigation**: Includes links to About, Sessions, Impact, and Register sections, with a sticky nav bar for easy access.
- **Hero Section**: Highlights the series with key stats (9 sessions, free tools, unlimited creative potential) and a call-to-action.
- **About Section**: Describes the series, its goals, and benefits, with an image showcasing collaboration.
- **Sessions Grid**: Displays 9 monthly sessions (October 2025 - June 2026) with titles, descriptions, and dates.
- **Testimonials**: Showcases participant feedback to highlight impact.
- **Registration Form**: Collects user details (name, email, club, role) for session sign-ups.
- **Footer**: Includes branding, resource links, social media icons, and copyright information.

## Technologies Used
- **HTML5**: Semantic structure for accessibility and SEO.
- **CSS**: Custom styles (`styles.css`) and Font Awesome for icons.
- **JavaScript**: Optional interactivity via `script.js`.
- **Fonts**: Google Fonts (Montserrat, Open Sans) for typography.
- **External Libraries**: Font Awesome CDN for icons.
- **Images**: Unsplash image for the About section.

## File Structure
```
├── index.html         # Main webpage
├── styles.css        # Custom CSS styles
├── script.js         # JavaScript for interactivity
└── sessions/         # Folder for individual session pages
    ├── session1.html
    ├── session2.html
    ├── ...
    └── session9.html
```

## Installation
1. Clone or download the repository.
2. Ensure an internet connection for CDN dependencies (Font Awesome, Google Fonts).
3. Open `index.html` in a web browser or serve via a local server (e.g., `python -m http.server`).

## Usage
- Navigate the site using the top navigation bar.
- Explore session details by clicking session cards (link to placeholder `sessionX.html` pages).
- Register via the form in the Register section (form submission requires backend integration).
- External links in the footer connect to Toastmasters resources and social media.

## Deployment
- Host on any static web server (e.g., GitHub Pages, Netlify, Vercel).
- Ensure `styles.css`, `script.js`, and the `sessions/` folder are included.
- Update session page links (`sessions/sessionX.html`) with actual content or routes if using a CMS or framework.

## Notes
- The registration form requires backend integration for processing submissions.
- Session pages (`session1.html` to `session9.html`) are referenced but not provided; create these files or update links as needed.
- The Unsplash image URL in the About section is subject to availability; replace if needed.
- Ensure compliance with Toastmasters branding guidelines (see linked Brand Manual).

## Contact
For inquiries, contact Leo Smith, District 106 Public Relations Manager, via Toastmasters District 106 channels.