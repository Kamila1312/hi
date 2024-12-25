Documentation for Delightful Bites Web Application

Overview
Delightful Bites is a web-based platform designed for a confectionery shop. The website showcases products, enables users to add items to a cart, and contact the shop via a form. It utilizes HTML, CSS, JavaScript, and the Bootstrap framework for a responsive, interactive, and visually appealing design.

Features

Navigation Bar
- A responsive navigation bar for seamless access to sections like About Us, Products, Cart, and Contact.
- Uses Bootstrap classes for styling and responsiveness.

Hero Section
- A visually striking section with a background image and welcoming message.
- Includes a "Shop Now" button that scrolls to the Products section.

About Us Section
- Describes the shop and its offerings in a clear and concise manner.

 Products Section
- Displays products with images, titles, descriptions, and prices in a card format.
- Includes "Add to Cart" buttons that allow users to dynamically add items to their cart.

Cart Section
- Lists items added to the cart with their prices and a "Remove" button.
- Dynamically calculates the total price of items in the cart.
- Provides a "Checkout" button that simulates payment confirmation.

Contact Section
- Features a form for users to submit their name, email, and message.
- Includes validation for required fields and a success message upon submission.

Footer
- A simple footer displaying copyright information.

Technologies Used

HTML
- Structured layout with semantic tags like `<section>`, `<nav>`, `<header>`, and `<footer>`.
- Forms and input elements for the contact section.

CSS
- Custom styling for buttons, cards, and sections.
- Pseudo-elements (`::after`) for decorative purposes.
- Flexbox for alignment and spacing.
- Bootstrap for responsive design.

 JavaScript
- Functions for managing the shopping cart, including adding/removing items and updating totals.
- Event listeners for handling button clicks and form submissions.
- DOM manipulation for dynamically updating the cart and form behavior.

Key Functions in JavaScript

`addToCart(name, price)`
- Adds an item to the cart array.
- Calls `renderCart()` to update the cart display.

`removeFromCart(index)`
- Removes an item from the cart by its index.
- Calls `renderCart()` to update the cart display.

`renderCart()`
- Updates the cart items and total dynamically in the DOM.

Form Submission
- Prevents default submission behavior.
- Displays a thank-you alert and resets the form fields.

 Responsive Design
- **Bootstrap Framework**: Used for layout and grid system.
- **Custom Flexbox Implementation**: Ensures proper alignment of items in the cart and product grid.

Project Goals
- Provide a user-friendly interface for browsing and purchasing confectionery items.
- Implement dynamic interactivity using JavaScript for a seamless shopping experience.
- Ensure responsiveness and compatibility across devices.

Usage Instructions

1.Navigating the Site:
   - Use the navigation bar to explore different sections.

2.Adding Products to Cart:
   - Click "Add to Cart" on a product card to include it in your cart.

3.Viewing and Managing the Cart:
   - Go to the Cart section to see added items and their total price.
   - Remove items using the "Remove" button.

4.Checkout Process:
   - Click "Checkout" to simulate a successful purchase.

5.Contacting the Shop:
   - Fill out the contact form and click "Submit" to send a message.

