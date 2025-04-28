# Decor – Dynamic Interior-Design Store (2020)

A **fully responsive** one-page website + mini e-shop built in early 2020 as a school project.  
The goal was to practice vanilla **JavaScript** (AJAX, JSON, localStorage), Bootstrap 4 layout, and a touch of jQuery/AOS for animations—without relying on any pre-made template.

[![Live Demo](https://img.shields.io/badge/Live-Demo-Open-blue?logo=github)](https://bobiz99.github.io/decor/)

---

## ✨ Key Features

| Area | What it does |
|------|--------------|
| **Hero Slider** | Images & copy are fetched via **AJAX** from `sliderSlike.json`, rendered into a Bootstrap carousel on page-load |
| **Off-canvas Menu** | “Hamburger” toggles an expanding nav (Bootstrap collapse) with **smooth-scroll** links |
| **Services Icons** | Font Awesome icons + titles pulled dynamically from `shippingIkonica.json` |
| **Mini Gallery** | Category thumbnails generated from `products.json`; AOS powers the fade-in animations |
| **Web Shop** | Products, categories & sub-categories all loaded by **AJAX** (`products.json`, `categories.json`); items filterable by category, price ⇡ / ⇣, name A → Z / Z → A |
| **Cart with localStorage** | `ADD TO CART` writes the product (id/qty) to localStorage; the `cart.html` table cross-references JSON + LS and lets users **increment, decrement, or remove** items |
| **Form Validation** | Contact form checks each field on **Submit** and shows inline error messages; date input auto-fills today’s date |
| **Google Maps** | Embedded map of store location via Google Maps JS API |
| **Responsive Design** | Bootstrap grid + custom media-queries ensure it looks good on phones, tablets & desktops |

---

## 🔧 Tech Stack

* **HTML5 & CSS3**
* **JavaScript (ES6)** & **jQuery** (utility DOM helpers)
* **AJAX / JSON / XML** data sources
* **Bootstrap 4** layout & components
* **Font Awesome 5** icons
* **AOS** (Animate On Scroll) library
* **Google Maps API**
* **LocalStorage** for cart persistence
* **Google Fonts**

_No template was used—layout, styling, and JS were coded from scratch for learning purposes._

