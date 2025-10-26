# 🏠 Airbnb Clone Backend — Use Case Diagram

## 📘 Overview
This document provides a visual representation of the **Airbnb Clone Backend Use Case Diagram**.  
The diagram illustrates how different actors (users and external systems) interact with the backend system to perform key functionalities such as **user registration**, **property listing management**, **booking**, and **payments**.

The use case diagram helps define the **scope** of the system, **user interactions**, and the **core processes** that support the overall business logic of an Airbnb-like platform.

---

## 🧩 Key Actors and Their Roles

| Actor | Description |
|--------|--------------|
| **Guest (User)** | Registers an account, searches for properties, books stays, makes payments, and leaves reviews. |
| **Host** | Manages property listings, responds to reviews, and handles booking requests. |
| **Admin** | Oversees the platform by managing users, listings, and monitoring payments. |
| **Payment Gateway** | External system responsible for processing guest payments and issuing payouts to hosts. |

---

## ⚙️ Core System Functionalities

The Airbnb Clone backend supports the following main use cases:

### 👤 User Management
- User Registration and Authentication (via email, password, or OAuth)
- Profile management (update name, contact info, profile photo)

### 🏡 Property Management
- Hosts can add, edit, or delete listings
- Each listing includes details such as title, location, price, amenities, and availability

### 🔍 Search and Filtering
- Guests can search for properties based on location, price range, guest capacity, or amenities
- Includes pagination and data optimization for large datasets

### 📅 Booking System
- Guests can create bookings for available properties
- Prevents double bookings and maintains booking statuses (pending, confirmed, canceled)
- Guests or hosts can cancel bookings under specific conditions

### 💳 Payments
- Integrates with secure payment gateways like Stripe or PayPal
- Supports multiple currencies and automated payouts to hosts
- Tracks payment status for each booking

### ⭐ Reviews and Ratings
- Guests can leave reviews and ratings for properties they have booked
- Hosts can respond to reviews to maintain engagement and trust

### 🔔 Notifications
- Sends real-time notifications for booking confirmations, cancellations, and payment updates

### 🛠️ Admin Management
- Admins can monitor platform activity
- Manage user accounts, property listings, and payments for compliance and quality control

---

## 🧠 Diagram Description

The **Use Case Diagram** below visually represents how each actor interacts with the backend system:

- **Guests** interact with the system to register, search, book properties, make payments, and review stays.  
- **Hosts** manage their listings, respond to reviews, and view booking requests.  
- **Admins** maintain platform integrity by managing users, listings, and payments.  
- **Payment Gateway** serves as an external entity handling financial transactions securely.

---

## 🖼️ Use Case Diagram

![Airbnb Clone Backend Use Case Diagram](https://github.com/benjamin-o-ansah/alx-airbnb-project-documentation/blob/main/use-case-diagram/use-case-diagram.png)

*Figure 1: Airbnb Clone Backend Use Case Diagram — depicting interactions among Guests, Hosts, Admins, and the Payment Gateway.*

---

## 🧾 Summary

This use case diagram serves as a **blueprint** for backend development, ensuring:
- All key system interactions are identified.
- Developers understand user-system relationships.
- Functional requirements align with real-world Airbnb workflows.


