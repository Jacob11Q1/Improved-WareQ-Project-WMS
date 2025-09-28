📦 WareQ WMS – Warehouse Management System

A professional warehouse management system (WMS) built with Django and MySQL, designed to handle inventory, suppliers, customers, and orders in a simple yet powerful way.

🚀 Features:

🔐 Authentication & User Management:
   -- Custom user model
   -- JWT authentication (via djangorestframework-simplejwt)
   --  Role-based permissions

📊 Dashboard:
  --  Overview of sales, purchases, inventory, and suppliers
  -- Recent activity logs

🧾 Orders Management:
 -- Create, update, and delete orders (sales & purchases)
 -- Order invoices & reports (PDF export support)

📦 Inventory Management:
 -- Track stock items (name, SKU, price, quantity)
 -- Supplier–item relationships
 -- Stock movement history

🧑‍🤝‍🧑 Customers & Suppliers:
 -- Manage customer profiles
 -- Manage suppliers and their items

🌐 REST API:
 -- CRUD endpoints for Customers, Suppliers, Items, and Orders
 -- JWT-secured API
 -- Filtering, search & ordering
 -- API docs with Swagger and ReDoc

🛠️ Tech Stack:
 -- Backend: Django 5, Django REST Framework
 -- Database: MySQL (PyMySQL)
 -- Frontend: Django templates + Bootstrap 5 + Crispy Forms
 -- Auth: JWT (SimpleJWT)
 -- Docs: Swagger & ReDoc (drf-spectacular, drf-yasg)
 -- Others: Django Filters, CORS headers, Widget Tweaks

⚙️ Installation

Clone the repo:

git clone https://github.com/Jacob11Q1/Improved-WareQ-Project-WMS.git
cd Improved-WareQ-Project-WMS/wareq_wms


Create & activate a virtual environment:

python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Linux/Mac
