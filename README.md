# Solavine Navigation & Dropdown Refactor — Odyssey Task

**Task Slug:** `solavine-nav-refactor`  
**Collection Family:** Product clone  
**Task Family:** Debugging  
**Verifier Family:** Programmatic  

---

## 📝 Overview

This is a self-contained software-engineering task for the Odyssey benchmark. The task requires an AI agent to refactor the navigation system of the **Solavine Senior Care** landing page (`index.html`).

The agent must fix a broken hybrid dropdown menu (desktop hover + mobile touch) and ensure that a background slideshow runs continuously without interruption. The core challenge lies in untangling conflicting CSS and JavaScript event handlers while preserving the exact visual design.

---

## 🎯 What the Agent Must Do

1. **Desktop (hover)** – Use pure CSS `:hover` to show/hide the "Services" dropdown (no JavaScript interference).
2. **Mobile (touch)** – Use a clean `click`/`touch` toggle to open/close the dropdown via JavaScript.
3. **Slideshow** – Ensure the cinematic background images rotate every 3 seconds regardless of user interaction with the nav.
4. **Mobile layout** – Fix the horizontal overflow so the dropdown fits within the viewport on narrow screens (< 768px).

---

## 📁 Bundle Structure
