<div align="center">

# 🛒 Flipkart Clone - Online Shopping Site
**A modern, responsive e-commerce frontend powered by Vanilla JavaScript.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![LocalStorage](https://img.shields.io/badge/Local_Storage-0052CC?style=for-the-badge&logo=icloud&logoColor=white)](#)

*Experience seamless shopping, cart management, and user authentication—all happening right in your browser!*

<br>

[✨ Features](#-interactive-features) • 
[🚀 Quick Start](#-getting-started) • 
[🔐 Demo Login](#-demo-credentials) • 
[🛠️ Tech Stack](#️-technical-details)

</div>

---

## ✨ Interactive Features

Click the sections below to explore what makes this platform special:

<details open>
<summary><b>🛍️ Dynamic Product Grid</b></summary>
<br>

- Products are rendered dynamically using JavaScript.
- Displays engaging emoji placeholders, star ratings, and real-time discount percentage calculations.
- Clean hover animations and responsive grid design that adapts to mobile screens.
</details>

<details>
<summary><b>🛒 Smart Cart Management</b></summary>
<br>

- Add products to your cart with a single click.
- Increase or decrease item quantities directly within the cart modal.
- Automatic price total calculation.
- Cart data persists across browser reloads using **Local Storage**.
</details>

<details>
<summary><b>🔐 Client-Side Authentication</b></summary>
<br>

- Secure-feeling login modal with animated entry/exit.
- Conditional UI updates: User Info bar replaces the login button upon successful entry.
- Safe logout functionality that clears session data and cart contents.
</details>

<details>
<summary><b>🔔 Toast Notifications</b></summary>
<br>

- Beautiful CSS-animated pop-up notifications slide in when you add an item, log in, log out, or checkout.
</details>

---

## 🚀 Getting Started

No installation or build tools are required! This project runs entirely in your browser.

1. **Download/Clone** the repository files to your local machine.
2. Ensure you have the following files in the same directory:
   - `index.html` (or `index_2.html`)
   - `styles.css`
   - `script.js`
3. **Open the HTML file** in any modern web browser (Chrome, Firefox, Safari, Edge).

---

## 🔐 Demo Credentials

To test the authentication and cart features, use the following pre-configured demo account:

> **Email:** `farhanfawad007@gmail.com`
> 
> **Password:** `1234567`

*Note: You must log in to add items to your cart or proceed to checkout!*

---

## 🛠️ Technical Details

<details>
<summary><b>View Project Architecture</b></summary>

- **UI/UX:** Styled using pure CSS3 with Flexbox and CSS Grid for layout management. Modals are built with z-index layering and `@keyframes` for smooth transitions.
- **State Management:** All application state (Cart items, User Session) is managed via the browser's `localStorage` API.
- **Vanilla JS:** Zero external libraries or frameworks. The DOM is manipulated entirely using native JavaScript (`document.createElement`, `addEventListener`, etc.).

```text
📦 Flipkart-Clone
 ┣ 📜 index.html    # The main layout, modals, and header
 ┣ 📜 styles.css    # Flipkart blue theme, grid layouts, and animations
 ┗ 📜 script.js     # Auth logic, cart arrays, and product database
```
</details>

---

<div align="center">
  <b>Happy Shopping! 🛍️</b><br>
  <i>A lightweight demonstration of frontend e-commerce capabilities.</i>
</div>
