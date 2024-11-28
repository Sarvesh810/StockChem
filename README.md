# 🧪 Chemical Inventory Tracker

A **Flutter**-based application designed to manage and track the inventory of chemical products. This app provides functionality to categorize products, track their weights and quantities, and support multiple account roles with specific permissions.

---

## ✨ Features

- **📦 Inventory Management**

  - Add, edit, or remove products.
  - Track each product's weight and quantity.
  - Organize products into customizable categories.

- **👥 User Roles**

  - 🔍 **Viewer Account**: Can only view the inventory.
  - ✍️ **Editor Account**: Can add, edit, or remove products and adjust quantities.

- **📱 User-Friendly Interface**
  - Simple and intuitive design for quick navigation and management.
  - Fully responsive interface.

---

## 🛠️ Tech Stack

- **🎨 Frontend**: [Flutter](https://flutter.dev/) (Dart)
- **☁️ Backend**: Firebase
- **📂 Database**: Firebase Firestore

---

## 💡 Usage

### Account Types:

1.  🔍 **Viewer Account**:
    - Can view product categories, names, weights, and quantities.
2.  ✍️ **Editor Account**:
    - Can add new products or categories.
    - Edit existing products, including updating weights and quantities.
    - Remove products from the inventory.

### Managing Products:

- Products are divided into categories for better organization.
- Each product includes:
  - **Name**: Product identifier.
  - **Category**: Classification of the product.
  - **Weight**: Weight of the product.
  - **Quantity**: Number of units available in the inventory.
