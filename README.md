# fawry-intern
# 🛒 Java Console e-ecommerce System

A layered Java console application that simulates a simple e-commerce  system. Customers can add products to a cart, view shipping and subtotal costs, and complete checkout, with support for expired items, stock validation, and shipment tracking.

---

## 🧱 Architecture

This project follows a **Layered Architecture**:
- **Model Layer**: Domain entities like `Product`, `Customer`, and `Shippable`
- **Service Layer**: Business logic for cart management, checkout, and shipping
- **UI Layer**: `Main` class simulating a user-driven console application

---

## ✅ Features

- Add products to cart with stock validation
- Handle expired products and out-of-stock errors
- Calculate:
  - Subtotal
  - Shipping fees (based on weight)
  - Total amount
- Simulate shipment for shippable items
- Print formatted checkout receipts and shipment notices
- Throw meaningful errors for:
  - Empty carts
  - Insufficient customer balance
  - Invalid product state

