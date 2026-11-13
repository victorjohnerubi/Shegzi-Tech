# Shegzi-Tech
Official web platform for Shegzi-Tech — a modern design, promotional merchandise, and precision printing company based in Ogun State, Nigeria. Features an interactive product customizer, live logo mockup preview, tiered bulk pricing calculator, dynamic portfolio filter, and automated EmailJS checkout.

# Shegzi-Tech — Design, Brand & Precision Printing Platform

Welcome to the official repository for **Shegzi-Tech**, a technology-driven graphic design, custom merchandise, and commercial printing company founded by **John Oluwasegun** and headquartered in **Ogun State, Nigeria**.

This web application gives businesses, event planners, and individuals a seamless e-commerce experience to customize products, preview their logos live, calculate bulk discounts, and request free digital proofs.

---

## Key Features

* **Live Product Customizer & Logo Preview:** Customers can upload their logo (`PNG`, `JPEG`, `SVG`) and preview it immediately on different product colors using the HTML5 `FileReader` API.
* **Dynamic Tiered Bulk Pricing:** Automatically calculates unit discounts in Naira (`₦`) based on order quantity and production speed (Standard vs. 24-Hour Rush).
* **Persistent Shopping Cart Drawer:** Slide-out cart powered by `localStorage` allowing multi-item customization and combined checkout.
* **Filterable Portfolio Gallery:** Interactive category filtering (`Custom Apparel`, `Gifts & Drinkware`, `Packaging & Labels`, `Event Signage`).
* **Automated Order & Proof Emails:** Integrated with **EmailJS** to send branded HTML order confirmations and proof requests without requiring a heavy backend server.
* **100% Certainty Guarantee Workflow:** Built-in customer reassurance policies, artwork guidelines, and FAQ sections.

---

## Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Black `#111111`, Orange `#FF6600`, and White palette), Vanilla JavaScript (ES6+)
* **State & Storage:** Browser `localStorage` for shopping cart persistence
* **Email Automation:** [EmailJS](https://emailjs.com) (`@emailjs/browser`)

---

## Project Structure

```text
shegzi-tech-web/
├── index.html          # Homepage (Hero, Categories, Certainty Guarantee, Reviews)
├── customizer.html     # Interactive Product Customizer & Live Pricing Engine
├── portfolio.html      # Filterable Recent Work Gallery (#BrandWithShegzi)
├── about.html          # Company Story & Founder Bio (John Oluwasegun)
├── services.html       # Full Design, Print & Packaging Service Catalog
├── contact.html        # Ogun State Studio Info, Quote Form & FAQs
├── legal/              # Privacy Policy, Artwork Guidelines & Return Policy
└── README.md           # Project Documentation
```

---

## Getting Started (Local Setup on Windows)

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd shegzi-tech
   ```

2. **Configure EmailJS:**
   * Create a free account at [EmailJS](https://emailjs.com).
   * Add your **Service ID**, **Template ID**, and **Public Key** inside the `<script>` tag of `customizer.html` and `contact.html`:
     ```javascript
     emailjs.init({ publicKey: "YOUR_PUBLIC_KEY" });
     ```

3. **Run the project:**
   * Open the folder in **VS Code** and launch with the **Live Server** extension, or double-click `index.html` to open it directly in your browser.

---

## About Shegzi-Tech

* **Founder & CEO:** John Oluwasegun
* **Location:** Ogun State, Nigeria (Nationwide Delivery)
* **Core Services:** Graphic & Brand Identity Design, Custom Apparel & Embroidery, Corporate Drinkware, Large-Format Signage, and Custom Product Packaging.

---

## License

&copy; 2026 **Shegzi-Tech**. All Rights Reserved.
