---
marp: true
title: "Product Documentation Presentation"
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

# Product Documentation Overview  
**Technical Writer: 23f2005057@ds.study.iitm.ac.in**

This slide deck demonstrates how Marp supports maintainable, version-controlled documentation.

---

# Key Features

- Custom theme  
- Page numbers  
- Background image  
- Math equations  
- Slide-level styling  

---

<!-- Background image slide using your file -->
<!-- wallpaperflare-cropped.jpg must be in the same folder -->
<!-- This syntax is VALID for Marp -->

<!--
backgroundImage: url('wallpaperflare-cropped.jpg')
backgroundSize: cover
-->

# System Architecture  
### (Background Image Slide)

This slide uses a local background image bundled with the documentation.

---

# Algorithmic Complexity

### Example Time Complexity

\[
T(n) = O(n \log n)
\]

### Example Space Complexity

\[
S(n) = \Theta(n)
\]

---

<style scoped>
section {
  background-color: #eef7ff;
  border-left: 10px solid #005bbb;
}
</style>

# API Documentation

- REST + JSON  
- Schema validation  
- Backward compatibility  

---

# Thank You!

Contact: **23f2005057@ds.study.iitm.ac.in**  
Marp presentation exportable to PDF, HTML, and PPT.

