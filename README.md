# Ecom - A Comprehensive Flutter Ecommerce Application

Ecom is a Flutter-based ecommerce mobile application developed as an academic project for the **Mobile Application Design Lab** course. The project is designed as a modern ecommerce UI application and front-end prototype that demonstrates the major workflows of a shopping platform, including authentication, product browsing, cart management, checkout, profile handling, order tracking, and other supporting modules.

The application focuses on clean UI design, modular implementation, reusable components, and a realistic user flow. It serves as both a learning project and a front-end prototype of a complete ecommerce mobile app.

---

## Project Overview

The goal of Ecom is to simulate the complete user journey of a modern ecommerce mobile application within a single Flutter project. Instead of showing only isolated screens, the application combines the main ecommerce workflows into one connected and organized system.

The project includes:

- Authentication flow
- Home screen with banners and featured products
- Product browsing and product detail views
- Search and filtering
- Shopping cart functionality
- Checkout and payment method flow
- Order history and order tracking
- Profile and account management
- Wishlist and address management
- Notifications, settings, help, and legal sections

This project emphasizes maintainability, modularity, and consistent mobile UI design.

---

## Objectives

The main objectives of this project are:

- To design and develop a Flutter-based ecommerce mobile application using a feature-based structure
- To implement the core user flows of a modern shopping application
- To build a reusable and visually consistent UI using shared widgets and centralized theming
- To demonstrate practical mobile app development through real-device testing, APK generation, and public publishing

---

## Core Features

- Authentication screens (Onboarding, Login, Register)
- Home dashboard with banners and featured products
- Product browsing, categories, and product details
- Search and filtering system
- Shopping cart with quantity update and total calculation
- Checkout and payment method flow
- Order history and order tracking
- Profile, wishlist, and address management
- Notifications, settings, help, and legal information pages

---

## Application Modules

The application currently includes the following major modules:

### Authentication
- Onboarding
- Login
- Registration

### Main Navigation
- Home
- Search
- Cart
- Profile

### Shopping Flow
- Categories
- Product Details
- Wishlist
- Checkout
- Payment Methods

### Orders and Account
- Order History
- Order Tracking
- Address Management
- Notifications
- Settings
- Help & Support

### Legal and Additional Screens
- Privacy Policy
- Terms of Service
- Licenses
- Reviews
- Security-related screens

---

## Technology Stack

- **Framework:** Flutter
- **Language:** Dart
- **IDE:** Visual Studio Code
- **State Handling:** ChangeNotifier
- **Build System:** Gradle
- **Java Environment:** Eclipse Temurin JDK 17
- **Android Tools:** Android SDK Command-line Tools

---

## Packages Used

The project uses several Flutter packages to improve UI quality and development efficiency, including:

- `cached_network_image`
- `flutter_svg`
- `carousel_slider`
- `google_fonts`
- `flutter_staggered_grid_view`
- `shimmer`

These packages support modern ecommerce-style UI design such as banners, image handling, typography, and responsive product presentation.

---

## Project Architecture

Ecom follows a **feature-based Flutter architecture**.

Instead of placing all screens and logic in one location, the project separates the application into organized feature modules.

The main layers are:

- **Presentation Layer** – screens and visible UI
- **Feature Layer** – authentication, cart, checkout, profile, orders, and related modules
- **Service Layer** – product and cart-related app logic
- **Core Layer** – theme, constants, and global configuration
- **Shared Widgets Layer** – reusable buttons, text fields, and product cards

This structure improves code readability, maintainability, and future scalability.

---

## Project Structure

lib/
- core/
  - constants/
  - theme/
- features/
  - address/
  - auth/
  - cart/
  - categories/
  - checkout/
  - help/
  - home/
  - legal/
  - main/
  - notifications/
  - onboarding/
  - order/
  - payment/
  - product/
  - profile/
  - reviews/
  - search/
  - security/
  - settings/
  - wishlist/
- models/
- services/
- shared/
  - widgets/
- main.dart

---

## Getting Started

To run this project successfully, make sure your development environment is properly configured.

### Prerequisites

Install the following tools before running the project:

- Flutter SDK
- Dart SDK
- JDK 17
- Android SDK
- Android platform-tools
- Visual Studio Code or Android Studio
- A connected Android device or emulator

---

## Installation

Clone the repository:

```bash
git clone https://github.com/itsrashedhasan/Ecom.git
cd Ecom
