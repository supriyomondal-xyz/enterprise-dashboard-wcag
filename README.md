# Enterprise Dashboard - Semantic HTML5 & WCAG 2.1 AA Compliant

> Task 3: Semantic HTML5 & Accessible Component Architecture - RabTech Academy

![W3C Validated](https://img.shields.io/badge/W3C-0%20Errors%200%20Warnings-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-Semantic-orange)
![WCAG](https://img.shields.io/badge/WCAG-2.1%20AA-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

Live, accessible, and fully semantic enterprise dashboard built with pure HTML5 following strict W3C and WCAG 2.1 AA standards.

**🔗 Live Demo:** `index.html` (Open directly or via GitHub Pages)
**📸 Validation Proof:** `Screenshot 2026-09-18 135712.png`

---

## ✅ Validation

**W3C Nu Html Checker:** 0 Errors, 0 Warnings
**Checked via:** https://validator.w3.org/nu/#textarea

![W3C Validation](./Screenshot%202026-09-18%20135712.png)

## ♿ Accessibility Features (WCAG 2.1 AA)

- **Skip to content link** for keyboard users
- **Semantic landmarks:** `<header>`, `<nav>`, `<aside>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **ARIA:** `aria-label`, `aria-labelledby`, `aria-describedby`, `aria-current`, `role="dialog"`
- **Forms:** Proper `<label for>`, `<fieldset>`, `<legend>`, `required`, `type="email"`
- **Table:** `<caption>`, `<thead>`, `<th scope="col">`, `<th scope="row">`
- **Images:** All with meaningful `alt` text
- **Focus management:** Visible focus states

## 🏗️ Semantic Structure

```html
header (banner)
  nav (primary)
aside (complementary navigation)
main
  section (metrics)
    article x3
  section (data table)
  section (form)
footer (contentinfo)
dialog (modal)
