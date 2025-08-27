# E-Commerce Backend API

A comprehensive Node.js backend application for e-commerce platforms with modern microservices architecture and extensive API endpoints.

## 🛠️ Technology Stack

- **Database**: MongoDB
- **Cloud Services**: Amazon Web Services (AWS)
- **Message Queue**: RabbitMQ
- **Search Engine**: Elasticsearch
- **Caching**: Redis
- **Event Streaming**: Apache Kafka
- **Web Server**: Nginx

## 🚀 Features

### Authentication & Authorization
- **Login** [Public] - User authentication
- **SignUp** [Public] - User registration
- **Logout** [User] - Secure user logout
- **Tokens** [User] - JWT token management

### Password Management
- **Change Password** [User] - Update user password
- **Forgot Password** [Public] - Password recovery initiation
- **Reset Password** [Public] - Password reset functionality

### Email Management
- **Send Email Verification** [User] - Email verification system

### User Management
- **Create New User** [Admin] - Admin user creation
- **Get All Users** [Public] - Retrieve user listings
- **Get User Data Using ID** [Public] - Fetch specific user details
- **Update User Details Using ID** [User] - Profile updates
- **Update User Profile Image Using ID** [User] - Profile picture management
- **Delete My Account** [User] - Account self-deletion
- **Delete User Using ID** [Admin] - Admin user removal

### Shopping Cart Services
- **Add Product To Cart** [User] - Add items to shopping cart
- **Reduce Product Quantity By One** [User] - Decrease item quantity
- **Increase Product Quantity By One** [User] - Increase item quantity
- **Get Cart** [User] - Retrieve cart contents
- **Delete Cart Item** [User] - Remove specific items
- **Delete Cart** [User] - Clear entire cart

### Review System
- **Create New Review** [User] - Submit product reviews
- **Query All Reviews** [Public] - Browse all reviews
- **Query Review Using ID** [Public] - Get specific review
- **Update Review Using ID** [User] - Edit user reviews
- **Delete Review Using ID** [User] - Remove user reviews

### Product Management
- **Query Products** [Public] - Browse product catalog
- **Query Product Using ID** [Public] - Get product details
- **Create New Product** [Seller] - Add new products
- **Update Product Details** [Seller] - Edit product information
- **Update Product Main Image** [Seller] - Change primary product image
- **Update Product Images** [Seller] - Manage product gallery
- **Delete Product Using ID** [User] - Remove products
- **Get Products Statistics** [Admin] - Product analytics
- **Top 5 Cheapest Products** [Public] - Budget-friendly options
- **Add Product Color** [Seller] - Color variant management
- **Add Product Size** [Seller] - Size variant management
- **Delete Product Color** [Seller] - Remove color options
- **Delete Product Size** [Seller] - Remove size options

### Favorites System
- **Get Favorite Products List** [User] - View wishlist
- **Add Product to Favorite List** [User] - Add to wishlist
- **Delete Product From Favorite List** [User] - Remove from wishlist
- **Check If Product In Favorite List** [User] - Verify wishlist status

### Discount Management
- **Generate Discount Code** [Admin] - Create promotional codes
- **Get Discount Amount** [User] - Calculate discounts
- **Get All Discount Codes** [Admin] - View all codes
- **Verify Discount Code** [User] - Validate promo codes
- **Delete Discount Code** [Admin] - Remove codes
- **Cancel Discount Code** [User] - Deactivate applied codes

### Order Management
- **Create New Order** [User] - Place orders
- **Query Orders** [User] - View order history
- **Query Order Using ID** [User] - Get order details
- **Cancel Order** [User] - Order cancellation
- **Update Order Status** [Admin] - Order status management

### Category Management
- **Create New Category** [User] - Add product categories
- **Query Categories** [Public] - Browse categories
- **Query Category Using ID** [Public] - Get category details
- **Update Category Details** [Admin] - Edit categories
- **Update Category Image** [Admin] - Category image management
- **Delete Category** [Admin] - Remove categories

### Additional Features
- **Multi-Language Support** - Internationalization ready

## 🔐 Permission Levels

- **[Public]** - Accessible to all users
- **[User]** - Requires user authentication
- **[Admin]** - Requires administrator privileges
- **[Seller]** - Requires seller/vendor privileges

## 🏗️ Architecture

This backend follows a microservices architecture pattern with:
- **MongoDB** for data persistence
- **Redis** for caching and session management
- **RabbitMQ** for asynchronous message processing
- **Elasticsearch** for advanced search capabilities
- **Kafka** for event streaming and real-time data processing
- **Nginx** for load balancing and reverse proxy

## 📝 API Documentation

The API provides comprehensive endpoints for a full-featured e-commerce platform, supporting multiple user roles and complex business logic including inventory management, order processing, and customer relationship management.

## 🌐 Multi-Language Support

The application includes internationalization features to support multiple languages for global e-commerce operations.

---

*This README was generated based on the project documentation. For detailed API specifications, please refer to the API documentation or contact the development team.*