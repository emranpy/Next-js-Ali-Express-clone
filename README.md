# 🛒 AliExpress Clone — Full-Stack Multi-Vendor Marketplace

A high-performance, production-ready multi-vendor e-commerce platform inspired by AliExpress.
Built with **Next.js, TypeScript, MySQL, Prisma, Clerk**, and other modern tools to deliver a global, scalable shopping experience.

---

## 🚀 Tech Stack

### **Frontend**

* **Next.js** (App Router)
* **TypeScript**
* **Tailwind CSS**
* **React Query / SWR** (data fetching)
* **Shadcn UI / Custom UI components**
* **Zustand / Context** (state management)

### **Backend**

* **Next.js Server Actions & API Routes**
* **MySQL** (production-grade relational DB)
* **Prisma ORM**
* **Redis** (caching, real-time counters, rate-limiting)
* **UploadThing / Cloudinary** (media uploads)

### **Auth & Security**

* **Clerk** (authentication + user management)
* **Middleware-based RBAC** for Admin/Seller/User roles

### **DevOps**

* **Vercel** (deployment)
* **PlanetScale / Neon / Local MySQL**
* **Docker** (optional)
* **Stripe** (if you add payments later)

---

## 🌍 Homepage

* Fully responsive, modern UI.
* Automatic country detection + manual location selector.
* Location-aware product sections (best sellers, trending, flash deals, etc.).
* Real-time search with instant suggestions (powered by Redis indexing or SQL LIKE queries).

---

## 🛍️ Product Page

* High-quality image swiper with zoom + drag.
* Complete variant system:

  * Sizes
  * Colors
  * Stock per variant
  * Variant-specific pricing & discounts
* Real-time **live viewer counter** using Redis pub/sub.
* Dynamic shipping logic:

  * Country-specific shipping fees
  * Store-level shipping rules
  * Free shipping worldwide or selected countries
* Full product content:

  * HTML description
  * Technical specifications
  * Q&A section
  * Related product recommendations
* Store card displaying seller info, ratings, and suggested stores.

---

## 🛒 Cart & Checkout

* Live-updating cart using server actions + optimistic UI.
* Auto-recalculates:

  * Prices
  * Shipping fees
  * Country changes
* Add/remove items, wishlist support.
* Checkout with full address management.
* Coupon code system with discount logic.

---

## 🛠️ Admin Dashboard

* Manage global marketplace settings:

  * Categories
  * Global offers
  * Store approvals
* Monitor sellers, orders, and marketplace activity.
* Suspend or verify stores for safety and quality.

---

## 🏪 Seller Dashboard

* Ultra-detailed product creation tools:

  * Variants
  * Specifications
  * HTML descriptions
  * Media uploads
  * Shipping rules per country
* Store-wide shipping configuration.
* Create & manage coupon codes.
* Advanced order management:

  * Product-level status
  * Shipping updates
  * Customer communication workflow

---

## 🔎 Standalone Features

### 🔍 Real-Time Search Page

* Lightning-fast filtering, sorting, and search results.

### 🏬 Store Pages

* Seller-specific listings
* Category filtering
* Seller info and engagement stats

### 🙍‍♂️ User Profiles

* Manage:

  * Orders
  * Reviews
  * Wishlists
  * Addresses
  * Followed stores
  * Account settings

---

## 📦 Project Overview

This project acts as a complete marketplace ecosystem, including:

* Multi-vendor architecture
* Role-based dashboards
* Country-aware shopping experiences
* Real-time features
* Dynamic shipping logic
* Full product + variant management
* Admin control center
* Scalable backend built on Prisma + MySQL
* Secure auth with Clerk

---


## 🧪 Status

✔️ Fully functional
✔️ Scalable
✔️ Production-ready
✔️ Extendable for payments, logistics APIs, and more


