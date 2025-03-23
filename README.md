# 🛍️ Product Management System

A simple web-based Product Management System built with **HTML**, **CSS**, **JavaScript**, and **Bootstrap**. It allows users to **add, edit, delete, filter, and sort products** with data saved using **localStorage**.

---

## 🔧 Features

### Product Fields

- **Product ID** (Auto-generated)
- **Product Name**
- **Product Image**
- **Price**
- **Description**

### Core Functions

- **Add Product** – Form with real-time validation
- **Edit Product** – Update details using URL query params
- **Delete Product** – With confirmation and success popup
- **View Products** – Displayed in card layout
- **Filter Products** – By ID, Name, Price, or Description
- **Sort Products** – By ID, Name, Price, or Description (asc/desc)
- **Responsive UI** – Bootstrap layout with 2-column design
- **Persistent Storage** – All data stored in `localStorage`

---

## ✅ Validation Rules

| Field            | Rules                                                                      |
| ---------------- | -------------------------------------------------------------------------- |
| **Name**         | Required, min **2 characters**                                             |
| **Image Upload** | Required for new products, valid image formats only (JPG/PNG), max **1MB** |
| **Price**        | Must be a number **greater than 0**                                        |
| **Description**  | Required, min **10 characters**                                            |
| **Real-Time**    | Fields validate instantly as the user types                                |

---

## 📦 How to Use

1. Click **"Add Product"** to create a new entry.
2. Use the **Edit** button to update product info.
3. Click **Delete** to remove a product (with confirmation).
4. Use **Filter inputs** to search specific products.
5. Use **Sort dropdowns** to organize products.
6. If no results are found, a clear message is shown.
7. Data is saved in `localStorage` and persists between sessions.

---

## 💡 Tech Stack

- HTML5
- CSS3
- Bootstrap 4
- JavaScript (ES6)
- LocalStorage

---
