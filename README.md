# 📦 WareQ – Warehouse Management System (WMS)

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Django](https://img.shields.io/badge/Django-5.0-green)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap-purple)
![Status](https://img.shields.io/badge/Status-In_Development-yellow)

> **WareQ-WMS** is a full-stack Warehouse Management System built with Django to simplify and streamline warehouse operations.  
> It provides real-time inventory tracking, efficient order handling, and insightful reporting for businesses of any size.

---

## ✨ Features

- 👤 **Customer Management** – Add, edit, track customers  
- 🏭 **Supplier Management** – Manage supplier data  
- 📦 **Inventory Control** – Track stock, availability & movements  
- 📝 **Orders (Sales & Purchases)** – Create, update & monitor orders  
- 📊 **Dashboard & Reports** – Visualize sales, purchases, and KPIs  

---

## 🛠 Tech Stack

- **Backend:** Django (Python)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** MySQL  
- **Hosting (planned):** AWS EC2 / RDS  
- **Version Control:** Git & GitHub  

---

## 📌 Roadmap (Phases)

- ✅ Phase 1: Authentication  
- ✅ Phase 2: Core Apps (Customers, Suppliers, Inventory, Orders)  
- ✅ Phase 3: CRUD Operations  
- ✅ Phase 4: Dashboard & Reporting  
- ✅ Phase 5: REST API Development  
- ✅ Phase 6: Testing & Validation  
- 🔜 Phase 7: Deployment (AWS/Docker)  

## 🏗 System Architecture

```text
 Users → Authentication (Django) → Core Apps (Accounts, Inventory, Orders, etc.) → Database (MySQL)


🚀 Quick Start

Clone and run locally:

# Clone repository
git clone https://github.com/Jacob11Q1/Improved-WareQ-Project-WMS.git
cd Improved-WareQ-Project-WMS

# Create virtual environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver


📈 Future Enhancements

Role-based permissions (Admin, Manager, Staff)

API integrations with ERP systems

Barcode/QR code support

Advanced analytics & forecasting

Mobile app support

🤝 Contributing

Contributions are welcome!
Fork the repo → Create a branch → Submit PR.

📜 License

MIT License © 2025 Jacob Qumseya
