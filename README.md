# STYLE US – Online Fashion Store

## Overview
STYLE US is a front-end e-commerce platform designed to provide a seamless shopping experience for browsing men's and women's fashion apparel. The site includes search functionality, category navigation, product detail pages, and cart management powered by LocalStorage.

## Features
- Browse products by categories (Men & Women)
- Keyword-based product search
- Product detail pages using URL parameters
- Add to cart, update quantity, and remove items
- Cart saved in LocalStorage for persistence
- Responsive and user-friendly interface

## Technologies Used
- **HTML5** – Page structure and layout  
- **CSS3** – Styling and responsive UI  
- **JavaScript (ES6)** – Dynamic rendering, interactivity, and cart logic  
- **LocalStorage** – Client-side data persistence  

## Project Structure

/assets
/images
/css
/js
index.html
product_list.html
product_detail.html
cart.html


## How It Works
- Products are loaded dynamically from JavaScript objects.
- Search queries filter available products in real time.
- Cart items are stored in `localStorage` and persist between sessions.
- Product details are passed through URL query parameters.

## Limitations
- No backend or server-side database  
- LocalStorage is device-specific  
- No user authentication or payment gateway  

## Future Enhancements
- Backend integration (Node.js / Django / PHP)
- User accounts and order history
- Payment gateway integration
- Admin dashboard for product management
- Advanced search filters and pagination
