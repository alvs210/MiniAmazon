# MiniAmazon
This project is a full-stack e-commerce platform designed to simulate an online marketplace. It supports core functionalities such as product creation, shopping carts, discount codes, user reviews, and inventory management. Created by Alveena Nadeem, Arely Sun, Ashton Caldwell, and Angel Huang.

### Demo Video: [CLICK HERE](https://drive.google.com/drive/folders/1ESl0VhQKTGmz-VdKjM0w_Ll4ygZy7GCr?usp=drive_link)

## Features

### User Accounts
- User registration and login with unique email and system-assigned IDs.
- Users can manage account details (excluding IDs), top up balances, and withdraw funds.
- Persistent user session management for enhanced experience.
### Products
- Browse, search, filter, and sort products by criteria such as price, category, and rating.
- Detailed product pages displaying seller availability, reviews, and a recommended products section.
- Product creation with duplicate product handling via alerts and suggestions.
- Quick view for product descriptions and enlarged images.
### Shopping Cart
- Persistent shopping cart with options to add, update, and remove items.
- Discount code support for item-specific, percentage-based, or total-cart discounts.
- Pagination for viewing up to 10 items per cart page.
- Empty cart view with a custom image and “Continue Shopping” button.
### Orders
- Cart submission converts into orders, updating user balances and seller inventories.
- Order history available for buyers, grouped by purchase date.
### Reviews
- Users can submit, edit, and delete reviews for products and sellers.
- Front-end star ratings for products and sellers, dynamically displayed based on review data.
- Dynamic review sorting (chronological and rating-based).
- Average ratings and review summaries displayed on product and seller pages.

## Additional Features
### Products
- Sorting capabilities for Product ID, Name, Price, Category, and Rating (ascending/descending).
- Filtering by minimum price, maximum price, and minimum rating.
- Recommended product section with paginated scrolling for related items.
### Cart
- Discount codes from a CSV file enable various discounts (e.g., single item or percentage-based).
- Pagination support with 10 items per cart page.
- Custom “empty cart” design with navigation options.
### Reviews
- Interactive star rating system that visually reflects review scores.
- Toggle feature to easily switch between product and seller reviews.
### Users
- Account deletion functionality included.

## Database Design

The relational database manages critical aspects of the platform, including:

- **Users**: Stores user information such as account balances and addresses.
- **Products**: Tracks product details, categories, and seller information.
- **Orders** and Purchases: Logs transactions, fulfillment status, and purchase history.
- **Reviews**: Records user reviews and ratings for both products and sellers.
- **Carts**: Manages items, discounts, and total costs per user session.

## Tools
- **Back-End**: Designed using Python and SQL, with parameterized queries to prevent SQL injection and hashed passwords for security.
- **Front-End**: Developed with CSS and HTML for an intuitive and responsive user interface.
- **Dataset**: Includes 200 users, 200 products, 2,500 purchases, and 2,000 reviews. Most data is synthetic, generated via scripts
