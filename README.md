# RevShop – Full Stack E-Commerce Web Application

RevShop is a full-stack e-commerce web application developed using Spring Boot, Oracle Database, Thymeleaf, and Bootstrap.
The system allows buyers and sellers to interact through a secure online marketplace.

Buyers can browse products, add items to cart, place orders, manage wishlist, write reviews, and track orders.
Sellers can manage inventory, update products, process orders, and handle returns and refunds.

The project follows MVC architecture and uses JWT-based authentication with role-based access control.

---

Developed By
Navuluru Vamsi Ujwal
Final Year Major Project

Technology
Spring Boot | Java | Oracle | Thymeleaf | Bootstrap

---

TECHNOLOGY STACK

Frontend  : HTML, CSS, Bootstrap
Backend   : Spring Boot
Language  : Java
Database  : Oracle XE
ORM       : Hibernate / JPA
Security  : Spring Security + JWT
Template  : Thymeleaf
Build Tool: Maven
IDE       : IntelliJ IDEA

---

SYSTEM ARCHITECTURE

Browser
↓
Controller Layer
↓
Service Layer
↓
Repository Layer
↓
Oracle Database

Layers:

Presentation Layer → Thymeleaf + Bootstrap
Controller Layer → Handles HTTP Requests
Service Layer → Business Logic
Repository Layer → Database Access
Database Layer → Oracle

---

FEATURES

Buyer Features

* Register / Login
* Browse Products
* Add to Cart
* Place Order
* Order History
* Wishlist
* Reviews
* Address Management
* Notifications
* Return Order

Seller Features

* Add Product
* Update Product
* Delete Product
* Manage Inventory
* View Orders
* Update Order Status
* Refund Processing

System Features

* JWT Authentication
* Role Based Login
* MVC Architecture
* Order Tracking
* Notification System
* Address Book
* Review System

---

PROJECT STRUCTURE

com.rev.app

controller

* BuyerController
* SellerController
* AuthController
* AddressController
* NotificationController

service
Interface
Impl

* OrderServiceImpl
* ProductServiceImpl
* CartServiceImpl
* ReviewServiceImpl
* FavoriteServiceImpl
* AddressServiceImpl
* NotificationServiceImpl

repository

* IProductRepository
* IOrderRepository
* ICartRepository
* IReviewRepository
* IFavoriteRepository
* IAddressRepository
* INotificationRepository
* IOrderItemRepository

entity

* User
* Product
* Cart
* CartItem
* Order
* OrderItem
* Address
* Payment
* Review
* Favorite
* Notification

config

* SecurityConfig
* JwtAuthFilter
* JwtUtil

dto
util
exception

---

DATABASE TABLES

USERS
PRODUCT
CART
CART_ITEM
ORDERS
ORDER_ITEMS
ADDRESS
PAYMENT
REVIEW
FAVORITE
NOTIFICATION

---

SECURITY

Spring Security
JWT Authentication
Role Based Authorization

JWT Flow

Login → Token Generated → Token Sent → Token Verified → Access Granted

---

DIAGRAMS INCLUDED

ER Diagram
Class Diagram
Use Case Diagram
Sequence Diagram
Activity Diagram

---

HOW TO RUN

1 Clone project

git clone https://github.com/your-username/revshop.git

2 Open in IntelliJ

3 Configure application.properties

spring.datasource.url=jdbc:oracle:thin:@localhost:1521:XE
spring.datasource.username=revshop
spring.datasource.password=revshop

4 Run

RevShopP2Application.java

5 Open

http://localhost:9090

---

FUTURE ENHANCEMENTS

Payment Gateway
Email Notifications
Cloud Deployment
Mobile App
AI Recommendation
Real-time Tracking

---

PROJECT TYPE

Final Year Major Project
Full Stack Spring Boot Application
