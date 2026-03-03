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
- Secondary: gradient `linear-gradient(90deg, #DCF180, #F0CD97, #35518A)` — used for hero background
- Accent: `#0061ff` (blue) — used for links, buttons, and highlights
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

