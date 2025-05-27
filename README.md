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


![image](https://github.com/user-attachments/assets/3d580a24-8a73-4ce7-95f7-6d252f0b2896)

![image](https://github.com/user-attachments/assets/3d4b4f47-a34c-4240-b791-4770234c2991)

![image](https://github.com/user-attachments/assets/127fc775-3115-483e-8f93-000346655a85)

![image](https://github.com/user-attachments/assets/291450ca-4c87-401e-911b-56a846df3733)


![image](https://github.com/user-attachments/assets/17d46379-545d-46c6-ad4d-cb3b8e375b97)


![image](https://github.com/user-attachments/assets/4c739a06-79d2-43bd-8a5a-bb41bed616ce)

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/sparepart_inventory.git
