
# AutomationExercise (automationexercise.com) — E-Commerce Test Requirements

Base URL: https://automationexercise.com/
No login is required to browse products or add items to the cart.

## Product Catalog
- The Products page (/products) is publicly accessible and displays the heading "All Products"
- The page lists product tiles with an image, title, price, an "Add to cart" button, and a "View Product" link
- Clicking "View Product" opens the product detail page, which includes a "Write Your Review" section

## Shopping Cart
- Clicking "Add to cart" on the Products page shows a confirmation modal with the text "Added!"
- The confirmation modal offers "View Cart" and "Continue Shopping" options
- Users can navigate to the cart page at /view_cart
- The cart page displays the heading "Shopping Cart"

## Authentication
- The login page is available at /login
- The login page displays a "Login to your account" section for returning users
- The login page also displays a "New User Signup!" section for new users
- Login/signup is optional — it is not required to browse products or use the cart
