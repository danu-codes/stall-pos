# 🏪 University Stall POS System

A lightweight, browser-based Point of Sale (POS) system designed for small university stalls and food vendors. This application works completely offline using **IndexedDB**, making it suitable for environments without a backend server.

## ✨ Features

- 📦 Product Management
  - Add new products
  - Upload product images
  - Delete products
  - Manage stock quantities

- 🛒 Point of Sale
  - Add products to cart
  - Increase/Decrease quantity
  - Automatic stock validation
  - Live cart total calculation

- 🧾 Billing
  - Generate professional PDF invoices
  - Automatic invoice numbering
  - Date and time stamping

- 📊 Sales Reports
  - Sales history
  - Revenue tracking
  - Download sales report as PDF

- 💾 Offline Storage
  - Uses IndexedDB
  - No internet connection required
  - No database server required

- 📱 Responsive Design
  - Desktop support
  - Tablet support
  - Mobile-friendly interface

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- IndexedDB
- jsPDF
- Tabler Icons

---

## 📂 Project Structure

```
University-Stall-POS/
│
├── index.html
├── README.md

```

*(If everything is inside a single HTML file, only `index.html` is required.)*

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/university-stall-pos.git
```

### Open the project

Simply open

```
index.html
```

in any modern web browser.

No installation required.

No server required.

No database required.

---

## 💾 Data Storage

This project stores all information inside the browser using **IndexedDB**.

Stored data includes:

- Products
- Product Images
- Stock Quantities
- Bills
- Sales Records

All data remains available after closing the browser.

---

## 📄 Invoice Features

Each generated invoice includes:

- Stall Name
- Invoice Number
- Date & Time
- Purchased Items
- Quantity
- Unit Price
- Total Amount

Invoices are exported as PDF.

---

## 📊 Sales Report

The application can generate a PDF report containing:

- Invoice Number
- Sale Date
- Units Sold
- Total Revenue

---


## 🌟 Future Improvements

- Product Categories
- Search Products
- Barcode Support
- Customer Details
- Discounts
- Tax Calculation
- Thermal Printer Support
- Excel Export
- Daily Sales Analytics
- Multi-user Authentication
- Cloud Backup

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📜 License

This project is released under the MIT License.

---

## 👨‍💻 Author

Developed by **DANUSHAN**

GitHub: https://github.com/danu-codes
