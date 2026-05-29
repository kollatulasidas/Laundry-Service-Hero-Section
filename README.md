
# 🧺 Laundry Service – Hero Section

A responsive Laundry Service landing page built using pure HTML5 and CSS3.
This project focuses on mastering layout structuring with `display: inline-block`, responsive design techniques, and clean UI styling without using Flexbox, Grid, or external frameworks.

---

## 📋 Project Overview

| Detail            | Information             |
| ----------------- | ----------------------- |
| Project Type      | Frontend Landing Page   |
| Technologies Used | HTML5, CSS3             |
| Layout Technique  | `display: inline-block` |
| Responsive Units  | `vw`, `vh`, `%`         |
| Responsive Design | Media Queries           |

---

## 🗂️ Project Structure

```bash id="a7p9x2"
project/
├── index.html
├── style.css
└── README.md
```

---

## ✅ Features

### 🧭 Responsive Navbar

* Logo aligned to the left
* Navigation links centered
* Username section aligned to the right
* Built entirely using:

  * `display: inline-block`
  * `vertical-align: middle`
* No Flexbox or float properties used

---

### 🎯 Hero Section

* Two-column responsive layout
* Left section contains:

  * Heading
  * Description text
  * CTA button
* Right section contains:

  * Laundry service illustration
* `max-width: 1400px` prevents excessive stretching on large screens
* Responsive spacing and typography using viewport units

---

### ✨ Hover Effects

* Navigation links:

  * Blue background
  * White text on hover
* CTA button:

  * Background darkens
  * Slight zoom effect using `transform: scale()`
* Smooth animations using `transition`

---

## 📱 Mobile Responsive Design

Media query added for smaller screens:

```css id="um47v8"
@media (max-width: 444px)
```

### Mobile Layout Adjustments

* Navigation menu hidden
* Hero sections stacked vertically
* Full-width CTA button
* Responsive image resizing
* Reduced padding for smaller devices

---

## 📐 CSS Concepts Practiced

| Concept                  | Usage                                 |
| ------------------------ | ------------------------------------- |
| `display: inline-block`  | Navbar and Hero section layout        |
| `vertical-align: middle` | Aligning inline-block elements        |
| `font-size: 0`           | Removing inline-block whitespace gaps |
| `max-width`              | Preventing layout stretching          |
| `transition`             | Smooth hover animations               |
| `transform: scale()`     | Button hover zoom effect              |
| `vw`, `vh`, `%` units    | Responsive sizing                     |
| Media Queries            | Mobile responsiveness                 |
| `box-sizing: border-box` | Predictable sizing behavior           |

---

## 🚀 How to Run the Project

1. Clone or download the repository

```bash id="k4n8r1"
git clone <repository-link>
```

2. Open the project folder

3. Run `index.html` in your browser

---

## 🔧 Future Improvements

* Convert layout from `inline-block` to Flexbox
* Add hamburger menu for mobile navigation
* Improve accessibility using semantic HTML
* Add subtle shadows and animations
* Add tablet breakpoint responsiveness
* Use `clamp()` for better responsive typography

---

## 📚 Learning Outcome

This project helped practice:

* Traditional CSS layout techniques
* Responsive web design fundamentals
* UI spacing and alignment
* Hover interactions and transitions
* Structuring clean HTML and CSS code

---

## 👨‍💻 Author

**Kolla Tulasidas**
Frontend Development Practice Project
