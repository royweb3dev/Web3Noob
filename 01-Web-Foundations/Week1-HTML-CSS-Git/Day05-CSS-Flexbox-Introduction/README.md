# Day 05: CSS Flexbox Introduction

## 📅 Phase 1 – Week 1: Web Foundations  
> **Roadmap Track**: Styling Layouts with CSS  
> **Focus**: Responsive Layouting using Flexbox

---

## 🎯 Learning Objectives

- Understand the core concepts of Flexbox layout model.
- Practice key Flexbox properties: `display: flex`, `justify-content`, `align-items`, `flex-direction`, `flex-wrap`, and `gap`.
- Apply Flexbox to real-world components such as navigation bars, social media buttons, and content grids.
- Create responsive and adaptive layouts without relying on floats or manual margins.

---

## 🧠 Key Concepts

| Property            | Description                                              |
|---------------------|----------------------------------------------------------|
| `display: flex`     | Turns an element into a flex container                   |
| `flex-direction`    | Defines the direction of the main axis (row or column)   |
| `justify-content`   | Aligns items on the main axis                            |
| `align-items`       | Aligns items on the cross axis                           |
| `flex-wrap`         | Allows items to wrap onto multiple lines                 |
| `gap`               | Defines space between items (modern alternative to margin) |

---

## 💻 Practical Implementation

**✔️ Implemented Components:**
- Flex-based navigation bar
- Responsive `.social-buttons` section using `flex-wrap` and `gap`
- Centered `.social-button` items with aligned icons

```css
nav ul {
  display: flex;
  justify-content: center;
  gap: var(--space-4);
  flex-wrap: wrap;
}

.social-buttons {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 10px;
}

.social-button {
  display: flex;
  justify-content: center;
  align-items: center;
}
