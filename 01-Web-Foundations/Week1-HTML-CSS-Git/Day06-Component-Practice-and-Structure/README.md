## Day 06: Component Practice & Structure

**Date:** 2025-08-05  
**Focus:** Structural Refactoring, Utility Classes, CSS Componentization

---

### ✅ Objectives Achieved

- Applied **modular CSS architecture** inside a single `styles.css` file using block-level comments.
- Extracted reusable utility classes:
  - `.btn`
  - `.mt-4`
  - `.shadow-md`
  - `.text-center`
- Cleanly separated layout zones into three primary areas:
  - `#skills` (Left Sidebar)
  - `#core` (Main Content)
  - `#projects` (Right Sidebar)
- Removed redundant CTA button (`Contact Me`) from the About section to maintain a cleaner UX.
- Maintained full compatibility with a two-file structure (`index.html` and `styles.css`) as required.
- Confirmed zero visual bugs and consistent responsive layout.

---

### 📦 Folder & File Structure

01-Web-Foundations/
└── Week1-HTML-CSS-Git/
└── Day06-Component-Practice-and-Structure/
├── index.html
└── styles.css

> No external folders or JS frameworks were introduced. The focus remains on mastering **semantic HTML** and **scalable CSS** in isolation.

---

### 💡 Key Learnings

- Building layout and style structure with **future component-based mindset** (preparation for React/Vue).
- Practicing **UI isolation** and **low coupling** via scoped CSS.
- Keeping call-to-actions minimal and strategic improves user flow.
- Naming CSS components and utilities semantically enhances long-term maintainability.

---

### 🛠️ Next Steps

Proceed to `Day 07 – Dark Mode System` where we will implement a fully accessible, toggleable color scheme using CSS Variables, media queries, and localStorage fallback.

---
