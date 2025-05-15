# E-Commerce-Website-for-Micro-IT

A basic E-Commerce website built with HTML, CSS (using Tailwind CSS), and JavaScript. It includes user authentication (login/registration), a product catalog, and a cart system, designed for a seamless shopping experience.

## Features
- **Login/Registration**: Users can register and log in to access the cart, with data stored in `localStorage`.
- **Product Catalog**: Displays products (Laptop, Headphones, Smartphone) with images sourced from Unsplash.
- **Cart System**: Add/remove items to/from the cart, view total, and checkout with a simple confirmation.
- **Responsive Design**: Styled with Tailwind CSS for a clean, mobile-friendly layout.

## Project Structure
- `index.html`: The main file containing the website's HTML, CSS (via Tailwind CDN), and JavaScript.
- No additional files are required as all logic and styling are embedded in `index.html`.

## Technologies Used
- **HTML**: Structure of the website.
- **CSS (Tailwind CSS)**: For responsive and modern styling, included via CDN.
- **JavaScript**: Handles dynamic functionality like cart management, user authentication, and DOM manipulation.
- **localStorage**: Used for storing user data temporarily.

Open `index.html` in a web browser to run the website locally.

## Usage
- Register a new account using the "Register" button.
- Log in with your credentials.
- Browse the product catalog and add items to your cart.
- View your cart, remove items if needed, and checkout.

## Screenshots
- **Product Catalog**  
 <img width="959" alt="Image" src="https://github.com/user-attachments/assets/5613c18e-e014-447f-a1bf-054f9acfd196" />

*The product catalog displaying available items with images.*

- **Cart Modal**


*The cart modal showing selected items and total.*

- **Login Page**
  
<img width="346" alt="Image" src="https://github.com/user-attachments/assets/bd1ca7b2-85b0-421b-b236-96c851a313e5" />

*The login modal for user authentication.*



## Future Improvements
- Add a backend (e.g., Node.js, Express) for persistent user data storage.
- Implement a payment gateway for real transactions.
- Expand the product catalog with categories and search functionality.
- Enhance security for user authentication (e.g., password hashing).
- Add unit tests for JavaScript functions using a framework like Jest.

