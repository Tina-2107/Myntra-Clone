# Myntra Clone

A front-end clone of the Myntra e-commerce homepage, built with plain **HTML** and **CSS** as a first web project.

## 📌 About

This project recreates the visual layout of Myntra's landing page — header with navigation and search, a promotional banner, product category grids, and a multi-column footer. No frameworks or JavaScript are used; it's pure HTML/CSS practice.

## 🗂️ Project Structure

```
web-projects/
├── index.html      # Main markup
├── styles.css       # All styling
├── image/            # Logo, banner, and category images
└── README.md
```

## 🚀 Getting Started

No build step required.

1. Clone or download this repository.
2. Make sure the `image/` folder (with `myntra_logo.webp`, `banner.jpg`, and the numbered product images) sits next to `index.html`.
3. Open `index.html` directly in your browser.

## ✨ Features

- Sticky-style header with logo, navigation links, search bar, and action icons (Profile / Wishlist / Bag)
- Promotional banner section
- "Categories to Cart" product grid
- "Shop by Categories" grid
- Multi-column footer with copyright notice

## 🐛 Known Issues / TODO

- [ ] Footer columns are currently duplicated — need unique headings/links per column (e.g. Customer Policies, Useful Links, Experience App)
- [ ] `class=".sale"` on category links should be `class="sale"` (invalid selector currently)
- [ ] Remove duplicate Material Symbols font `<link>` tags in `<head>`
- [ ] Add `<meta charset="UTF-8">` and a responsive viewport meta tag
- [ ] Add `alt` text to all product/category images
- [ ] Add media queries — layout currently isn't mobile-responsive
- [ ] Fix stray extra `}` and empty `padding-right` declaration in `styles.css`
- [ ] Make search, wishlist, and bag icons interactive (future JS pass)

## 🛠️ Built With

- HTML5
- CSS3 (Flexbox)
- [Material Symbols](https://fonts.google.com/icons) for icons

## 📄 License

This is a personal learning project, built for educational purposes only. Not affiliated with or endorsed by Myntra.
