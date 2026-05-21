# 🧺 Laundry Service – Hero Section

A responsive Hero Section web page for a laundry service, built using pure HTML and CSS (no Flexbox, no frameworks).

---

## 📋 Project Overview

| Detail | Info |
|---|---|
| Project Type | Frontend Web Page |
| Tech Used | HTML5, CSS3 |
| Layout Method | Display Inline-Block |
| Units Used | Viewport units (`vw`, `vh`) |

---

## 🗂️ File Structure

```
project/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
└── README.md       # Project documentation
```

---

## ✅ Features

### Navbar
- Logo aligned to the **left**
- Navigation links (**Home, Service, About Us, Contact Us**) centered using `display: inline-block`
- Username pill aligned to the **right**
- Built using `display: inline-block` and `vertical-align: middle` — **no Flexbox, no floats**

### Hero Section
- Two-column layout using `display: inline-block` on `.left` and `.right`
- **Left div** — Heading, description paragraph, and CTA button
- **Right div** — Laundry illustration image
- `max-width: 1400px` on `.hero` prevents content from stretching on large screens
- All sizing uses **viewport units** (`vw`, `vh`) for responsiveness

### Hover Effects
- Nav links change to a **blue fill with white text** on hover
- CTA button darkens and **scales up slightly** on hover
- Both use `transition: 0.3s` for smooth animation

---

## 🚀 How to Run

1. Clone or download the project folder
2. Open `index.html` in any browser

---

## 📐 CSS Concepts Used

| Concept | Where Applied |
|---|---|
| `display: inline-block` | Navbar logo, nav, user — Hero left & right columns |
| `vertical-align: middle` | Aligning navbar elements on the same baseline |
| `font-size: 0` / `font-size: 16px` | Removing whitespace gaps between inline-block children |
| `text-align: center` | Centering the navbar and nav links |
| `max-width` | Capping hero width on large screens |
| `transform: scale()` | Button zoom on hover |
| `transition` | Smooth hover animations on links and button |
| `vw / vh units` | Font sizes, padding, spacing throughout |

---

## 👤 Author

**Kolla Tulasidas**  
Assignment: Hero Section – Laundry Service Web App