# Frontend Portfolio - Task 1

A modern, accessible portfolio website built with semantic HTML and vanilla CSS.

## Quick Start (Run this project locally)

```bash
# Clone the repository
git clone https://github.com/your-username/task-1.git

# Navigate into the project folder
cd task-1

# Start a local server
npx serve
```

### You should see:

```
┌───────────────────────────────────────────┐
│                                           │
│   Serving!                                │
│                                           │
│   - Local:    http://localhost:3000       │
│   - Network:  http://10.232.221.10:3000   │
│                                           │
│   Copied local address to clipboard!      │
│                                           │
└───────────────────────────────────────────┘
```

### Then open your browser and visit:

- **Local access:** `http://localhost:3000`
- **Network access (other devices):** `http://10.232.221.10:3000`

> **Tip:** The local address is automatically copied to your clipboard!

---

## Project Overview

This is a frontend developer portfolio page that demonstrates:

- Semantic HTML5 structure
- Accessibility best practices
- Responsive design
- Modern CSS (Grid, Flexbox, Custom Properties)
- W3C validated code (0 errors)

---

## Features

| Feature | Implementation |
|---------|----------------|
| Semantic HTML | `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, `<footer>` |
| Heading Hierarchy | H1 → H2 → H3 (logical outline) |
| Form Labels | Every input has associated `<label>` |
| Keyboard Navigation | Visible `:focus-visible` states on all interactive elements |
| CSS Variables | 15+ design tokens (`--accent-neon`, `--dark-space`, etc.) |
| REM Units | 100% rem-based sizing (accessibility friendly) |
| Hover Effects | Smooth transitions on cards and buttons |
| Responsive | Works on 1280px, 1024px, and 768px breakpoints |

---

## Built With

- **HTML5** - Semantic structure
- **CSS3** - Styling, animations, layouts
- **Google Fonts** - Outfit & JetBrains Mono
- **No frameworks or libraries** - 100% vanilla

---

## Project Structure

```
Task-1/
├── index.html          # Main HTML document
├── styles.css          # All styles (external, no inline)
└── README.md           # This file
```

---

## Validation Status

| Validator | Status |
|-----------|--------|
| [W3C HTML Validator](https://validator.w3.org/) | 0 errors, 0 warnings |

**Fix applied:** Escaped `&` to `&amp;` in Google Fonts URL to pass validation.

---

## Accessibility Highlights

- Skip navigation link for keyboard users
- `:focus-visible` rings on all interactive elements
- Semantic landmarks for screen readers
- Proper heading hierarchy
- All form inputs have `<label>` elements
- `aria-label` and `aria-hidden` where appropriate
- Sufficient color contrast

---

## Responsive Breakpoints

| Breakpoint | Target | Layout Behavior |
|------------|--------|-----------------|
| > 1024px | Desktop | 3-column cards, 2-column blog |
| 768px - 1024px | Tablet | 2-column sidebar, stacked nav |
| < 768px | Mobile | Single column, stacked everything |

---

## CSS Custom Properties (Design Tokens)

```css
:root {
  /* Colors */
  --dark-space: hsl(224, 25%, 9%);
  --accent-neon: hsl(150, 100%, 43%);
  --accent-violet: hsl(280, 80%, 65%);
  
  /* Fonts */
  --primary-font: 'Outfit', sans-serif;
  --code-font: 'JetBrains Mono', monospace;
  
  /* Spacing */
  --radius-s: 0.25rem;
  --radius-m: 0.5rem;
  --radius-l: 0.75rem;
  
  /* Transitions */
  --transition-ease: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
}
```

---

## Run on Different Ports

If port 3000 is busy, serve on a different port:

```bash
npx serve -l 8080
```

Then visit: `http://localhost:8080`

---

## Screenshot

<img width="1879" height="917" alt="image" src="https://github.com/user-attachments/assets/f0d4caa7-89ed-45b2-8666-26ff7f151777" />
<img width="1868" height="907" alt="image" src="https://github.com/user-attachments/assets/323bfab9-ae3c-4404-b3df-17d5421f0cfb" />
<img width="1728" height="909" alt="image" src="https://github.com/user-attachments/assets/801a4c2b-2d9b-4702-9146-9ead490ae733" />
<img width="1604" height="910" alt="image" src="https://github.com/user-attachments/assets/62585a58-21a1-46d9-9635-f9225508c81b" />
<img width="1493" height="770" alt="image" src="https://github.com/user-attachments/assets/3c4e12f0-6846-4be7-b714-dc67050b08ce" />
<img width="1488" height="895" alt="image" src="https://github.com/user-attachments/assets/747fd2a5-eea2-4b79-9185-5b8b72d80e5d" />
<img width="1589" height="881" alt="image" src="https://github.com/user-attachments/assets/d54c259b-45e4-47b2-854a-2f69107f901b" />


## License

This project is for demonstration purposes.

---

## Acknowledgments

- W3C Validator for HTML standards
- WCAG 2.1 for accessibility guidelines
- Google Fonts for Outfit & JetBrains Mono

---

## Support

For questions or feedback:
- Open an issue in this repository
- Email: Vaishnavi@pradhan.dev

---

**Built with semantic HTML, vanilla CSS, and a focus on accessibility.** 
```

---

##Quick Copy-Paste Version (Minimal)

If you want a shorter version:

```markdown
# Task-1 - Frontend Portfolio

## Run Locally

```bash
npx serve
```

**Expected output:**
```
┌───────────────────────────────────────────┐
│   Serving!                                │
│   - Local:    http://localhost:3000       │
│   - Network:  http://10.232.221.10:3000   │
└───────────────────────────────────────────┘
```

## Features

- Semantic HTML (header, nav, main, article, aside, footer)
- W3C Validated (0 errors)
- Accessible (focus states, labels, skip link)
- REM units only
- CSS custom properties
- Responsive (1280px, 1024px, 768px)

## Tech Stack

- HTML5
- CSS3 (vanilla, no frameworks)
- Google Fonts

## Validation

W3C HTML Validator: 0 errors, 0 warnings

## Author

Vaishnavi Pradhan | Vaishnavi@pradhan.dev
