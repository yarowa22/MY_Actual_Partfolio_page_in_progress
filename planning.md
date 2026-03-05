# Planning Document — Portfolio Landing Page

## 1. Portfolio Purpose and Target Audience
This portfolio is a personal landing page. The target audience is teachers, potential employers, and students who want to learn about my skills and projects. The purpose is to present my background and skills

## 2. Content Plan for the Landing Page
The landing page (index.html) will include:
- A **hero section** with a welcome message and a call-to-action button
- A **about section** with a short introduction and profile image
- A **skills section** listing my current technical skills
- A **contact section** with an email link and contact form link
- A **navigation bar** linking to About, Skills, Contact, and future project pages
- A **footer** with copyright information

## 3. Design Decisions

### Colors
- Primary: `#27385b` (dark navy blue) — used for header, footer, and contact section
- secondary: gradient `linear-gradient(90deg, #DCF180, #F0CD97, #35518A)` — used for hero background
- Accent: gradient `linear-gradient(0deg, #0061FF, #60EFFF)` — used for links, buttons, and highlights
- Background: `#f8f9fa` (light gray) — used for page body

### Typography
- Font family: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`
- Base font size: browser default (16px)
- Headings use `font-weight: 700` and scaled sizes (h1: 2.5rem, h2: 2rem, h3: 1.5rem)
- Line height: 1.6 for readability

### Layout
- Max content width: 1200px centered with `margin: 0 auto`
- Flexbox used for header layout and button groups
- Sticky header so navigation stays visible while scrolling

## 4. Navigation Structure
The nav bar contains links to:
- **Home** (index.html) — returns to landing page
- **About** (about.html) — personal background 
- **Contact** (contact.html) — contact form and social links
- **Skills** - navigates to skills section on home page(not a link)

## 5. Wireframe Sketch
(for better understanding please try to view from "Code")

[ HEADER: Logo | Nav: Home About Contact ]
[ HERO: Big heading + subtitle + button ]
[ ABOUT: Text left | Image right ]
[ SKILLS: Unordered list + card ]
[ CONTACT: Email link + button ]
[ FOOTER: Copyright ]


## 6. Tools Used
- **VS Code** — code editor
- **Live Server extension** — local preview in browser
- **Git & GitHub** — version control and repository hosting
- **GitHub Pages** — free static site hosting
- **Brave browser DevTools** — debugging layout and CSS


## 7. Discussion of HTML/CSS Evolution

HTML has evolved from a simple document markup language (HTML 1.0, 1993) into a rich semantic standard. HTML5 (2014) introduced semantic elements like `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>`, replacing generic `<div>` tags and making pages more accessible and machine-readable. Source: [MDN Web Docs — HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

CSS has evolved from basic inline styling to a powerful layout and design system. CSS3 introduced features like custom properties (variables), flexbox, grid, gradients, transitions, and media queries — all of which are used in this project. Source: [MDN Web Docs — CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## 8. HTML Tags I Used and Why

 `<nav>`  Wraps the navigation links — tells browsers and screen readers this is site navigation 
 `<section>`  Groups related content (hero, skills, contact) into meaningful blocks 
 `<figure>` / `<img>` Displays the profile image with semantic meaning; 
 `<footer>` Marks the bottom of the page with copyright info — semantic and good for SEO 

## 9. CSS Properties I Implemented and Why

 `font-family` with fallbacks  Ensures text renders consistently across different operating systems 
 `border-radius`  Rounds corners on cards and buttons, making the design feel modern and friendly 
 `position: sticky`  Keeps the header visible as the user scrolls — improves usability 
 `transition`  Adds smooth hover animations on buttons and cards — improves user experience 