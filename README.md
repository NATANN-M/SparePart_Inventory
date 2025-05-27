# 🧰 Spare Part Inventory Management System

A lightweight PHP-based inventory management system for managing spare parts, stock levels, staff, and sales reports. Ideal for small to mid-sized businesses, with features like sales tracking, staff management, and PDF export using DomPDF.

---

## 📁 Folder Structure

├── admin/ # Admin views (manage parts, staff, reports)
│ ├── assets/ # CSS, JS, and images
│ ├── include/ # Shared includes & templates
│ └── *.php # Admin pages (dashboard, reports, etc.)
├── controllers/ # Business logic (add, update, delete, sell)
├── dompdf/ # DomPDF library for PDF generation
├── public/ # Public accessible pages (login, view inventory)
├── uploads/ # Uploaded images or files
├── config.php # Configuration (DB and BASE_URL)
├── db.php # Database connection
├── index.php # Redirects to login or dashboard
└── .htaccess # Routing rules



---

## 🚀 Features

- 🧾 Add, update, and delete spare parts
- 👨‍🔧 Manage staff accounts and access
- 🛒 Sell parts with transaction logging
- 📈 Filterable sales reports
- 📄 Export reports to PDF (using DomPDF)
- 🗓 Daily summary of sales
- 🔐 Simple login/logout system
- 🗂 Organized MVC-like folder structure

---

## ⚙️ Technologies Used

- PHP (vanilla, no framework)
- MySQL
- HTML/CSS (Bootstrap)
- JavaScript (basic interactivity)
- [DomPDF](https://github.com/dompdf/dompdf) for PDF generation
- .htaccess for clean URLs (optional)

---

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/sparepart_inventory.git
