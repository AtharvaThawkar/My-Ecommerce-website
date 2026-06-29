# 🛍️ MyShop — E-Commerce Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

A responsive and visually appealing **E-Commerce frontend website** built using HTML5, CSS3, and Bootstrap 4. This project demonstrates UI design skills, CSS animations, Bootstrap components, and responsive web design principles.

---
 
## 🌐 Live Demo

> 🔗 **[View Live Demo](https://myshopproject1.netlify.app/)**

---

## ✨ Features

- 🧭 **Responsive Navbar** — with dropdown category menu, Login & Register buttons
- 🎨 **Animated Hero Section** — CSS keyframe animation cycling through product categories (Watches, Clothes, Smartphones, Laptops) with color transitions
- ⭐ **Ratings Section** — Google & Facebook style rating cards with star ratings
- 🛒 **Product Cards** — with smooth hover overlay effects showing Cart, Wishlist & View icons
- 🎠 **Product Carousel** — Bootstrap carousel for featured/pride products
- 📋 **About Section** — company information with image
- 📬 **Contact Section** — enquiry form with full name, email, phone & message fields
- 🔐 **Login & Register Modals** — Bootstrap modal popups for authentication UI
- 📱 **Fully Responsive** — works on mobile, tablet & desktop using Bootstrap grid

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure & semantic markup |
| CSS3 | Styling, animations, clip-path effects |
| Bootstrap 4.6 | Responsive grid, components, modals |
| Bootstrap Icons | Icon library |
| Google Fonts (Caveat) | Custom typography |
| jQuery | Bootstrap JS dependency |

---
## 📁 Folder Structure

```
MyShop-Ecommerce/
│
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles & animations
└── Images/             # All project images
    ├── Main.png        # Logo
    ├── Background.png  # Hero & About section image
    ├── s1.png          # Product images
    ├── s2.png
    ├── goog.png        # Google rating logo
    ├── fb.png          # Facebook rating logo
    ├── cart.png        # Cart icon
    ├── heart.png       # Wishlist icon
    ├── view.png        # View icon
    └── so1-3.png       # Carousel images
```

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Edge)
- No installation required — pure frontend project

### Run Locally
1. **Clone the repository**
```bash
git clone https://github.com/AtharvaThawkar/ecommerce-website.git
```

2. **Navigate to the project folder**
```bash
cd ecommerce-website
```

3. **Open in browser**
```bash
# Simply open index.html in your browser
# Or use Live Server in VS Code
```

---

## 🎨 Key CSS Highlights

### Animated Category Text
```css
/* CSS keyframe animation cycling through product categories */
@keyframes changetextanimation {
    25%  { content: "Watches";     color: red;        }
    50%  { content: "Clothes";     color: lightgreen; }
    75%  { content: "Smartphones"; color: blue;       }
    100% { content: "Laptops";     color: yellow;     }
}
```

### Hero Section Clip-path
```css
/* Creative polygon shape on the hero/jumbotron */
clip-path: polygon(50% 0%, 100% 0, 100% 35%, 100% 70%, 100% 100%, 34% 80%, 0 100%, 0% 70%, 0% 35%, 0 0);
```

### Product Card Hover Overlay
```css
/* Smooth overlay effect on product card hover */
#overlay { opacity: 0; transition: opacity 0.8s; }
.card:hover #overlay { opacity: 1; }
```

---

## 🔮 Future Improvements

- [ ] Add JavaScript for working Login / Register functionality
- [ ] Connect backend (Node.js + Express) for form submissions
- [ ] Add MongoDB database for storing products & users
- [ ] Implement real shopping cart with add/remove/total
- [ ] Add product search and filter functionality
- [ ] Integrate payment gateway (Razorpay / Stripe)
- [ ] Add product detail page
- [ ] Convert to full MERN Stack application

---

## 📚 What I Learned

- Responsive web design using Bootstrap 4 grid system
- CSS animations using `@keyframes` and `animation` properties
- Creative CSS effects — `clip-path`, hover transitions, overlays
- Bootstrap components — Navbar, Modals, Carousel, Cards
- UI/UX design principles for e-commerce platforms
- Structuring a multi-section webpage with semantic HTML5

---

## 👨‍💻 Author

**Atharva Pramod Thawkar**

[![GitHub](https://img.shields.io/badge/GitHub-AtharvaThawkar-181717?style=flat-square&logo=github)](https://github.com/AtharvaThawkar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Atharva_Thawkar-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/atharvathawkar)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<div align="center">
  <b>⭐ If you found this project helpful, please give it a star!</b>
</div>
