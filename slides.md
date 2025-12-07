---
marp: true
title: "Product Documentation Presentation"
description: "Technical Writer Presentation using Marp"
paginate: true
footer: "© 2025 — Documentation Team"
theme: custom-theme
---

<style>
/* ===========================
   Custom Marp Theme
   =========================== */

section {
  font-family: 'Segoe UI', sans-serif;
  color: #1a1a1a;
}

h1 {
  color: #005bbb;
  font-weight: 700;
}

p {
  font-size: 1.1rem;
}

footer {
  color: #777;
}

/* Page number styling */
section::after {
  content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  position: absolute;
  bottom: 20px;
  right: 40px;
  font-size: 0.8rem;
  color: #999;
}
</style>

<!--
Custom theme registration
-->
<!--
theme: custom-theme
-->

# Product Documentation Overview  
**Technical Writer: 23f2005057@ds.study.iitm.ac.in**

Welcome to the official documentation presentation.  
This slide deck demonstrates Marp features for maintainable, version-controlled documentation.

---

# Features of This Documentation

- Custom Marp theme  
- Page numbers  
- Background images  
- Mathematical equations  
- Slide-level styling  
- Git-friendly Markdown format

---

<!-- Slide with background image -->
<!-- Use any public image URL or local image -->
<!--
backgroundImage: url('wallpaperflare-cropped.jpg')
backgroundSize: cover
-->

# Product Architecture  
### (Background Image Slide)

Our system follows a modular architecture optimized for scalability, speed, and reliability.

---

# Algorithm Performance

We document computational behavior using mathematical notation:

### Example: Time Complexity

\[
T(n) = O(n \log n)
\]

### Example: Space Complexity

\[
S(n) = \Theta(n)
\]

---

# Custom-Styled Slide

<style scoped>
section {
  background-color: #eef7ff;
  border-left: 10px solid #005bbb;
}
h1 {
  color: #003f7f;
}
</style>

# API Contracts

- REST + JSON interface  
- Strict schema validation  
- Backwards compatibility guaranteed

---

# Thank You!

Documentation maintained in version control and exportable to:

- PDF  
- HTML  
- PowerPoint (via Marp CLI)

Contact: **23f2005057@ds.study.iitm.ac.in**

