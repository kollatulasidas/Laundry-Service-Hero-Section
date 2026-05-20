# 🧺 Laundry Service – Hero Section

A responsive Hero Section web page for a laundry service, built using pure HTML and CSS (no Flexbox, no frameworks).

---

## 📋 Project Overview

| Detail | Info |

| Project Type | Frontend Web Page |
| Tech Used | HTML5, CSS3 |
| Layout Method | Float, Position, Display Inline |
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
- Navigation links (**Home, Service, About Us, Contact Us**) centered using `position: absolute`
- Username pill aligned to the **right**
- Built using `float` and `position` — **no Flexbox**

### Hero Section
- Two-column layout using `float: left` and `float: right`
- **Left div** — Heading, description paragraph, and CTA button
- **Right div** — Laundry illustration image
- Uses `height: 100vh` so the section **fits the screen without scrolling**
- All sizing uses **viewport units** (`vw`, `vh`) for responsiveness

---

## 🚀 How to Run

1. Clone or download the project folder
2. Open `index.html` in any browser


## 📐 CSS Concepts Used

| Concept | Where Applied |
|---|---|
| `float: left / right` | Logo, Nav columns, Hero columns |
| `overflow: hidden` | Clearfix on `.navbar`, `.hero` |
| `position: absolute` | Centering the nav |
| `transform: translate(-50%, -50%)` | Perfect centering of nav |
| `display: block` | Button, image |
| `height: 100vh` | Hero full-screen fit |
| `vw / vh units` | Font sizes, padding, spacing |

---

## 👤 Author

**Kolla Tulasidas**  
Assignment: Hero Section – Laundry Service Web App  
