#  Amazon Frontend Clone

A pixel-faithful, responsive clone of the Amazon e-commerce homepage built with pure HTML, CSS, and JavaScript — no frameworks required.

---

##  Preview

The clone replicates the following key UI sections:

| Asset | Description |
|---|---|
| `amazon_logo.png` | Header logo |
| `hero_image.jpg` | Hero/banner — "Find gifts for dads who have it all" |
| `box1_image.jpg` | Fashion & Apparel collage |
| `box2_image.jpg` | Fashion & Apparel collage (variant) |
| `box3_image.jpg` | Samsung Galaxy S23 Ultra — Electronics |
| `box4_image.jpg` | Beauty & Makeup products |
| `box5_image.jpg` | Pet Supplies — dog & cat |
| `box6_image.jpg` | Toys & Kids |
| `box7_image.jpg` | Wardrobe & Storage organizers |
| `box8_image.jpg` | Health & Personal Care |
| `box8_image_1_.jpg` | Home & Furniture — desk setup |

---

##  Project Structure

```
amazon-clone/
│
├── index.html               # Main HTML page
├── style.css                # All styles (responsive + layout)
├── script.js                # Interactivity (navbar, carousel, etc.)
│
├── assets/
│   ├── amazon_logo.png
│   ├── hero_image.jpg
│   ├── box1_image.jpg
│   ├── box2_image.jpg
│   ├── box3_image.jpg
│   ├── box4_image.jpg
│   ├── box5_image.jpg
│   ├── box6_image.jpg
│   ├── box7_image.jpg
│   ├── box8_image.jpg
│   └── box8_image_1_.jpg
│
└── README.md
```

---

##  Features

- ✅ **Sticky Navigation Bar** — Logo, search bar, account/cart links
- ✅ **Hero Banner Carousel** — Full-width promotional banner with sliding animation
- ✅ **Category Grid (Box Layout)** — 8-box product category cards with hover effects
- ✅ **Responsive Design** — Mobile, tablet, and desktop breakpoints
- ✅ **Footer** — Multi-column links, back-to-top button, Amazon branding

---

##  Sections Mapped

### 1. Header / Navbar
- Amazon logo (`amazon_logo.png`)
- Delivery location selector
- Search bar with category dropdown
- Sign in / Account & Lists / Returns / Cart

### 2. Hero Banner
- Full-width promotional image (`hero_image.jpg`)
- Text overlay: *"Find gifts for dads who have it all"*
- Left-aligned CTA button

### 3. Product Category Boxes

| Box | Image | Category Label |
|-----|-------|----------------|
| 1 | `box1_image.jpg` | Fashion |
| 2 | `box2_image.jpg` | New Arrivals in Fashion |
| 3 | `box3_image.jpg` | Electronics |
| 4 | `box4_image.jpg` | Beauty & Personal Care |
| 5 | `box5_image.jpg` | Pet Supplies |
| 6 | `box6_image.jpg` | Toys & Games |
| 7 | `box7_image.jpg` | Home Storage & Organisation |
| 8 | `box8_image.jpg` / `box8_image_1_.jpg` | Health & Household |

### 4. Footer
- Back to top banner
- Multi-column links (Get to Know Us, Make Money with Us, etc.)
- Amazon logo, copyright notice

---

##  Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- No build tools or package managers needed

### Run Locally

```bash
# Clone the repository
git clone https://github.com/your-username/amazon-clone.git

# Navigate into the project folder
cd amazon-clone

# Open in browser
open index.html
# or simply double-click index.html
```

---

##  Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Flexbox, Grid, animations, media queries |
| Vanilla JavaScript | Carousel, navbar interactions, scroll behavior |

---

##  Responsive Breakpoints

| Breakpoint | Target Device |
|---|---|
| `< 480px` | Mobile phones |
| `480px – 768px` | Large phones / small tablets |
| `768px – 1024px` | Tablets / small laptops |
| `> 1024px` | Desktops and large screens |

---

## ⚠️ Disclaimer

> This project is built **purely for educational purposes** and is not affiliated with, endorsed by, or connected to Amazon.com, Inc. in any way. All images and the Amazon logo are used solely for UI demonstration and learning. Do not use this project for commercial purposes.

---

## Acknowledgements

- Inspired by [Amazon.com](https://www.amazon.com)
- Product and lifestyle images used for UI mockup only

---

##  License

This project is open-source under the [MIT License](LICENSE).
