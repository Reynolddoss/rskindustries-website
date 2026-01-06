# RSK Industries Website

A professional B2B/B2C wholesale marketing and distribution website for RSK Industries, built with HTML, CSS, and vanilla JavaScript.

## About

RSK Industries is a wholesale marketing & distribution company dealing in:
- Plastic water storage tanks
- Masala products (spices)
- Areca leaf disposable plates, cups & glasses
- Eco-friendly disposable products

## Features

- **Professional Design**: Clean, modern wholesale-focused design with trust-building elements
- **Responsive Layout**: Fully responsive design that works on all devices
- **Four Main Pages**:
  - Home: Hero section, product categories, trust indicators, and company highlights
  - Products: Detailed product listings with categories and features
  - About Us: Company story, mission, vision, values, and target markets
  - Contact: Contact form and business information
- **Interactive Elements**:
  - Mobile-friendly navigation menu
  - Smooth scrolling
  - Form validation
  - Hover effects and animations
  - Scroll-triggered animations

## Design Guidelines

### Color Scheme
- **Primary**: Dark Blue (#1a4d6e) / Green (#2d8659)
- **Secondary**: White (#ffffff) / Light Grey (#f5f5f5)
- **Accent**: Green (#4caf50) for eco-friendly feel

### Typography
- **Headings**: Poppins (Google Fonts)
- **Body**: Inter (Google Fonts)

## File Structure

```
rskindustries-website/
├── index.html          # Home page
├── products.html       # Products page
├── about.html          # About Us page
├── contact.html        # Contact page
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── script.js       # JavaScript functionality
├── assets/
│   └── images/         # Images and logos
└── README.md           # Project documentation
```

## Getting Started

1. Clone or download this repository
2. Open `index.html` in a web browser
3. No build process or dependencies required - pure HTML, CSS, and JavaScript

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Updating Contact Information
Edit the contact details in:
- Footer section of all HTML files
- Contact page (`contact.html`)

### Adding Products
Add new products in `products.html` by duplicating the product card structure:

```html
<div class="product-card">
    <div class="product-image-placeholder">
        <span>💧</span>
    </div>
    <h3>Product Name</h3>
    <p class="product-description">Product description...</p>
    <ul class="product-features">
        <li>✓ Feature 1</li>
        <li>✓ Feature 2</li>
    </ul>
    <a href="contact.html" class="btn btn-outline">Request Quote</a>
</div>
```

### Changing Colors
Modify CSS variables in `css/styles.css`:

```css
:root {
    --primary-color: #1a4d6e;
    --secondary-color: #2d8659;
    --accent-color: #4caf50;
    /* ... */
}
```

## Form Handling

The contact form currently shows a success message on submission. To integrate with a backend:

1. Update the form submission handler in `js/script.js`
2. Replace the simulated submission with an actual API call
3. Add server-side validation and email sending functionality

## License

See LICENSE file for details.

## Contact

For inquiries about RSK Industries, visit the [Contact page](contact.html).

---

Built with ❤️ for RSK Industries
