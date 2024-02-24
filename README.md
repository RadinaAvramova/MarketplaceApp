# Ruby on Rails – Marketplace App with Stripe Connect
Welcome to the Ruby on Rails – Marketplace App with Stripe Connect project! This repository contains a Ruby on Rails application for building a marketplace platform with payment processing capabilities using Stripe Connect. The Marketplace App allows users to create accounts, list products or services for sale, and securely process payments between buyers and sellers.

## Features
1. **User Authentication:** Provides user authentication and authorization functionalities, allowing users to sign up, log in, and manage their accounts securely.

2. **Product Listing:** Enables users to create listings for products or services they wish to sell on the marketplace, including details such as product description, price, and images.

3. **Shopping Cart:** Implements a shopping cart feature for users to add products to their cart and proceed to checkout for payment.

4. **Payment Processing with Stripe Connect:** Integrates Stripe Connect for secure payment processing, enabling transactions between buyers and sellers on the marketplace.

5. **Order Management:** Manages orders and transactions between buyers and sellers, tracking order status, payment details, and shipping information.

## Installation
To set up the Marketplace App:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/MarketplaceApp.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd MarketplaceApp

3. **Install Dependencies:** Install Ruby on Rails dependencies using Bundler:

bundle install

4. **Set Up Database:** Create and migrate the database by running:

rails db:create

rails db:migrate

5. **Configure Environment Variables:** Set up environment variables for Stripe API keys and other sensitive information in your Rails application configuration.

6. **Start the Server:** Start the Rails server using the following command:

rails server

7. **Access the Application:** Access the Marketplace App by navigating to http://localhost:3000 in your web browser.

## Usage
1. **User Registration:** Sign up for a new account as a buyer or seller on the marketplace.

2. **Product Listing:** Create listings for products or services you wish to sell, providing detailed descriptions and pricing information.

3. **Shopping:** Browse through listings, add products to your shopping cart, and proceed to checkout for payment.

4. **Payment Processing:** Complete payment securely using Stripe Connect, which supports various payment methods such as credit/debit cards and digital wallets.

5. **Order Management:** Manage orders and transactions, view order history, and track order status through the marketplace dashboard.

## Customization
1. **User Roles and Permissions:** Customize user roles and permissions to control access to certain features and functionalities based on user type (e.g., buyer, seller, administrator).

2. **UI/UX Customization:** Customize the user interface and user experience of the marketplace platform to match branding requirements and enhance usability.

3. **Additional Features:** Extend the marketplace app with additional features such as reviews and ratings, messaging between users, advanced search functionality, and social sharing.
