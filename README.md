# Food Munch 🍽️

A responsive food delivery landing page built with plain HTML and CSS. The site introduces the Food Munch brand, highlights why customers should choose it, showcases the menu, explains delivery & payment options, and links out to social media.

## Live Sections

- **Header / Navigation** – Sticky top bar with logo and links to page sections (Why Choose Us, Explore Menu, Delivery & Payment, Follow Us).
- **Banner** – Full-viewport hero section with a background image, heading, tagline, and call-to-action buttons ("View Menu" / "Order Now").
- **Why Choose Us** – Three feature cards (Food Service, Fresh Food, Best Offers) explaining the brand's value proposition.
- **Explore Menu** – A grid of menu category cards (Starters, Soups, Seafood, Main Course, Noodles, Salads, Desserts, etc.) each with a "View All" link.
- **Organic Produce** – Two-column layout pairing an image with copy about fresh, organic ingredients.
- **Delivery and Payment** – Reversed two-column layout describing hassle-free payments and order tracking, plus supported payment method icons (Visa, MasterCard, PayPal, American Express).
- **Follow Us** – Social media icon links (Twitter/X, Facebook, Instagram, WhatsApp) rendered as inline SVGs.
- **Footer** – Logo, contact email, and address.

## Tech Stack

- **HTML5** – Semantic markup (`header`, `nav`, `main`, `section`, `article`, `footer`)
- **CSS3** – Flexbox-based layouts, custom classes, and media queries for responsiveness
- No external CSS frameworks or JavaScript — a lightweight, dependency-free build

## Responsive Design

The layout adapts across breakpoints using CSS Flexbox and a `768px` media query:

- **Mobile** – Navigation links stack and wrap below the logo; two-column sections stack vertically.
- **Tablet & Desktop (≥ 768px)** – Navigation aligns to the right of the logo; two-column sections (Organic Produce, Delivery & Payment) sit side by side, with the `.reverse` variant flipping the image/content order.

## Project Structure

```
.
├── file.html   # Page markup
├── file.css    # Styles
└── README.md   # Project documentation
```

> Tip: Feel free to rename `file.html` and `file.css` to `index.html` and `style.css` (updating the `<link>` reference) for a more conventional project layout.

## Getting Started

1. Clone or download this repository.
2. Open `file.html` directly in your browser, **or** serve it locally:
   ```bash
   npx serve .
   ```
3. View the site at the served URL (or just double-click `file.html`).

No build step, package manager, or dependencies are required — it's plain HTML/CSS.

## Assets

All images (logo, banner background, feature icons, menu photos, payment icons) are hosted externally via CloudFront and referenced by URL in the HTML — no local image assets are needed to run the project.

## Browser Support

Built with standard CSS Flexbox and media queries, so it works in all modern browsers (Chrome, Firefox, Edge, Safari).

## License

Add your preferred license here (e.g., MIT) if you plan to open-source this project.
