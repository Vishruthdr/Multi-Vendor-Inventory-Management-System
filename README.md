# 📦 Multi-Vendor Inventory Management System

A Django-based web application that integrates multiple vendor data sources, normalizes product data, and provides a centralized inventory management system with a dashboard.

---

## 🚀 Features

- 🔌 Simulated Vendor APIs (3 different formats)
- 🔄 Data Normalization into a unified schema
- 🛢 MySQL Database integration
- 📦 Centralized Product Management
- 📊 Dashboard with inventory insights
- 🔍 Product search functionality
- ⚠️ Low stock alerts
- 🔗 REST APIs for data access

---

## 🧩 System Workflow

1. Fetch product data from multiple vendor APIs  
2. Normalize data into a standard format  
3. Store data in MySQL database  
4. Provide APIs to access inventory  
5. Display data using dashboard UI  

---

## 🏗 Tech Stack

- **Backend:** Django (Python)
- **Database:** MySQL
- **Frontend:** HTML, Bootstrap
- **API Testing:** Postman / Browser

--

- ⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone -https://github.com/Vishruthdr/Multi-Vendor-Inventory-Management-System
cd multi-vendor-inventory-system

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Configure Database
Update your MySQL credentials in:
settings.py

4️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate

5️⃣ Run the Server
python manage.py runserver



