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

- ✅ Semantic HTML5 structure
- ✅ Accessibility best practices
- ✅ Responsive design
- ✅ Modern CSS (Grid, Flexbox, Custom Properties)
- ✅ W3C validated code (0 errors)

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

*(Add a screenshot of your portfolio here)*

```
![Portfolio Screenshot](./screenshot.png)
```

---

## Requirements Checklist

- [x] Header with navigation
- [x] 3 article cards (title, date, excerpt, read-more link)
- [x] Sidebar with newsletter signup form
- [x] Footer
- [x] 6+ semantic HTML elements
- [x] Proper heading hierarchy (H1 → H2 → H3)
- [x] All form inputs have associated labels
- [x] W3C validator: 0 errors
- [x] External CSS (no inline or style tags)
- [x] 5+ CSS custom properties
- [x] REM units only
- [x] Optimized for 1280px viewport
- [x] Hover states on cards
- [x] Focus states on all interactive elements

---

## Author

**Vaishnavi Pradhan**

- Portfolio: *(your website)*
- GitHub: *(your GitHub profile)*
- Email: Vaishnavi@pradhan.dev
- Location: Pune, India

---

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

**Built with semantic HTML, vanilla CSS, and a focus on accessibility.** ✅
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
```

---

## How to Add This to Your GitHub Repo

1. **Create the README file:**
   - In your `Task-1` folder, create a file named `README.md`
   - Copy the content above into that file

2. **Commit and push:**
```bash
git add README.md
git commit -m "Add README file with setup instructions"
git push origin main
```

3. **On GitHub:** The README will automatically appear on your repository's main page

---

The README shows anyone visiting your GitHub repo exactly how to run your project - starting with `npx serve` - just like you see in your terminal!
