# 🛒 Toko Online Backend API

This is the backend REST API for a simple e-commerce application built with **Express.js**, **TypeScript**, **Prisma**, and **MySQL**.

---

## 🚀 Tech Stack

- **Node.js + Express.js**
- **TypeScript**
- **Prisma ORM**
- **MySQL**
- **JWT (JSON Web Token)** for authentication
- **bcrypt** for password hashing
- **dotenv** for environment variables

---

## 📦 Features Checklist

### ✅ Authentication
- [x] Register user (`/api/auth/register`)
- [x] Login user (`/api/auth/login`)
- [x] JWT authentication
- [x] Protected route `/me` to get current user profile

### ✅ User
- [x] Role support: `admin`, `customer`
- [ ] Admin-only route protection

### ✅ Product
- [ ] Get all products (`GET /api/products`)
- [ ] Get single product by ID or slug
- [ ] Create product *(admin only)*
- [ ] Update product *(admin only)*
- [ ] Delete product *(admin only)*

### ✅ Cart
- [ ] Add item to cart
- [ ] View cart items
- [ ] Remove item from cart

### ✅ Order
- [ ] Checkout cart to order
- [ ] View user orders
- [ ] View order details
- [ ] Update order status *(admin only)*

---
