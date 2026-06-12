[README.md](https://github.com/user-attachments/files/28873002/README.md)
<div align="center">

# 🌐 Akash Tiwari — Personal Portfolio Website

[![Live Preview](https://img.shields.io/badge/Portfolio-Live%20Preview-c8893a?style=for-the-badge&logo=googlechrome&logoColor=white)](https://akashtiwari232.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akash-tiwari-b87963188/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akashtiwari232)
[![Email](https://img.shields.io/badge/Email-Contact-c8893a?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akashtiwari232@gmail.com)

<br/>

**A premium single-page portfolio built in pure HTML, CSS & Vanilla JS — no frameworks, no dependencies.**

*Crafted with an amber & brown theme, scroll-triggered animations, and a fully responsive layout.*

<br/>

![Portfolio Preview](https://img.shields.io/badge/sections-9%20sections-c8893a?style=flat-square) ![Size](https://img.shields.io/badge/size-~870KB-5c3d1e?style=flat-square) ![No Framework](https://img.shields.io/badge/framework-none-lightgrey?style=flat-square) ![Responsive](https://img.shields.io/badge/responsive-✓-green?style=flat-square)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Sections](#-sections)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Customization](#-customization)
- [Project Structure](#-project-structure)

---

## 🧭 Overview

This is my personal portfolio website — a **single-file, zero-dependency** digital CV built from scratch using HTML5, CSS3, and Vanilla JavaScript. It showcases my experience as a Software Engineer at TCS, my AI/ML projects, skills, certifications, and achievements in a polished, interactive format.

**Design language:** Warm amber (`#c8893a`) & deep brown (`#5c3d1e`) on a cream base — intentional, premium, and consistent across every section.

---

## 📄 Sections

| # | Section | Description |
|---|---------|-------------|
| 01 | **Landing / Hero** | Name, designations, intro paragraph, CTA buttons, social links |
| 02 | **About Me** | Professional summary, profile photo, Mission & Vision cards |
| 03 | **Work Experience** | TCS (TCS-iON) & EICE Technology with quantified achievements |
| 04 | **Education** | B.Tech CSE — SRM Institute of Science and Technology |
| 05 | **Projects** | 5 personal projects with outcomes and tech tag pills |
| 06 | **Skills** | 6 skill categories with animated progress bars |
| 07 | **Certifications** | 8 certifications with provider badges |
| 08 | **Achievements** | Research paper + TCS AI Friday win, animated stat counters |
| 09 | **Contact** | Floating-label form (mailto) + contact info panel |

---

## ✨ Features

### 🎨 Design
- Warm **amber & brown** colour palette with cream backgrounds
- **Playfair Display** serif for headings + **DM Sans** for body text
- **JetBrains Mono** for labels and code-style tags
- Consistent `AT` logo / favicon in gold — appears in browser tab

### 🎞️ Animations
- **Hero:** Staggered fade-slide entrance, social icon pop-in with bounce
- **About:** Profile photo slides in from left, Mission/Vision cards flip in 3D (Y-axis cascade)
- **Experience:** Cards alternate left/right slide-in, curtain-open left panel, staggered bullet points
- **Projects:** Blur-to-sharp entrance, rubber-band pill tag bounce
- **Skills:** Grid wave scale-in, progress bars count from 0% to actual value in sync
- **Certifications:** Waterfall cascade with random tilt → snap flat, mouse-follow tilt on hover
- **Achievements:** Spring/bounce zoom-in, Ken Burns image pan, animated badge glow
- **Contact:** Diagonal slide-in from opposing corners, floating label animation, shimmer send button

### 📱 Responsive
- **4 breakpoints:** `1200px` · `900px` · `600px` · `380px`
- Hamburger menu with smooth open/close for tablet & mobile
- All grids reflow to single column on small screens
- Font sizes fluid with `clamp()` — never breaks at any viewport

### 🔧 Functional
- **Smooth scroll** — offset-corrected for fixed nav (64px) on all anchor links
- **Profile photo upload** — click or drag-and-drop to swap photo (in-browser, no server)
- **Contact form** — opens mailto with pre-filled name, email, subject and message
- **Stat counters** — animate up on scroll into view
- **Skill bars** — animate on scroll with percentage count-up

---

## 🛠 Tech Stack

```
HTML5          — Semantic structure, single file
CSS3           — Custom properties, Grid, Flexbox, @keyframes, IntersectionObserver hooks
Vanilla JS     — Scroll animations, hamburger menu, photo upload, smooth scroll, counters
Google Fonts   — Playfair Display, DM Sans, JetBrains Mono
No frameworks  — Zero npm, zero build step, zero dependencies
```

---

## 🚀 Getting Started

### Option 1 — Just open it

```bash
# Clone the repo
git clone https://github.com/akashtiwari232/portfolio.git
cd portfolio

# Open directly in browser — no server needed
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

### Option 2 — Local dev server (optional, for live reload)

```bash
# Using Python
python3 -m http.server 8000

# Using Node (npx)
npx serve .

# Then open http://localhost:8000
```

> No build step. No npm install. No config. It just works.

---

## 🌍 Deployment

### GitHub Pages (recommended — free & instant)

```bash
# 1. Rename the file to index.html if needed
mv akash_tiwari_portfolio.html index.html

# 2. Push to GitHub
git add index.html
git commit -m "feat: add portfolio"
git push origin main

# 3. Enable GitHub Pages
# Go to repo → Settings → Pages → Source: main branch → / (root) → Save
# Your portfolio will be live at: https://akashtiwari232.github.io/portfolio
```

### Netlify (drag & drop)

1. Go to [netlify.com](https://netlify.com) → **Add new site → Deploy manually**
2. Drag & drop the `index.html` file
3. Done — live in seconds with a `*.netlify.app` URL

### Vercel

```bash
npx vercel --name akash-portfolio
```

---

## 🎨 Customization

All content is hardcoded in the single HTML file. To update:

| What to change | Where to find it |
|---|---|
| Name, email, phone | Search `Akash Tiwari` / `akashtiwari232` |
| GitHub / LinkedIn URLs | Search `github.com/akashtiwari232` |
| Profile photo | Find `id="profileImg"` — replace `src` with your image path or base64 |
| Colour theme | Edit CSS variables at top: `--amber`, `--brown`, `--cream` |
| Skill percentages | Find `data-target="90"` style attributes in the Skills section |
| Add/remove sections | Each section is wrapped in `<section id="...">` blocks |

### Colour variables (easy theming)

```css
:root {
  --amber:       #c8893a;   /* primary accent */
  --amber-light: #e8a84e;   /* hover/gradient accent */
  --amber-dark:  #9b6420;   /* deep accent */
  --brown:       #5c3d1e;   /* headings */
  --cream:       #f5f0e8;   /* page background */
  --charcoal:    #2c2016;   /* dark panels */
}
```

---

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Entire portfolio — HTML + CSS + JS in one file
│
└── README.md               # This file
```

> Everything is self-contained in `index.html`. The profile photo is embedded as a base64 data URI, so the file works completely offline with no asset dependencies.

---

## 📬 Contact

| Channel | Link |
|---|---|
| 📧 Email | [akashtiwari232@gmail.com](mailto:akashtiwari232@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/akash-tiwari-b87963188](https://www.linkedin.com/in/akash-tiwari-b87963188/) |
| 🐙 GitHub | [github.com/akashtiwari232](https://github.com/akashtiwari232) |
| 📞 Phone | +91-8949484169 |

---

<div align="center">

Made with ❤️ by **Akash Tiwari**

*Engineering Intelligence. Building Tomorrow.*

⭐ If you found this useful, consider giving it a star!

</div>
