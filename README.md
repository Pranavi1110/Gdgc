# E-Commerce Platform

This is a simple e-commerce platform built using React that allows users to browse products, add them to a cart, and manage the cart items (increase/decrease quantities, remove items). The app uses `axios` to fetch products from a public API, and provides filtering functionality with a search bar.

## Features

- Product Listing: Displays a list of products fetched from the Fake Store API.
- Cart Management: Users can add products to the cart, increase or decrease quantities, and remove items.
- Search Functionality: Users can search for products by their titles.
- Price Details: Displays the total price of the items in the cart.

## Technologies Used

- React: For building the UI and managing component states.
- Axios: For making HTTP requests to the Fake Store API.
- CSS: For basic styling.

## Components

- App: The main component that holds the overall structure of the platform.
- ProductList: Displays the list of products with an option to add items to the cart.
- Cart: Shows the products added to the cart and provides options to adjust quantities or remove products.
- PriceDetails: Displays the total price of items in the cart.
- SearchBar: Provides the search functionality to filter products based on their titles.
