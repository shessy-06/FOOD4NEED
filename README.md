# 🍽️ FOOD4NEED – Food Donation Portal

FOOD4NEED is a web-based food donation platform developed using **Python Django**.  
The project aims to reduce food wastage by connecting **donors**, **NGOs**, and **administrators** on a single platform.

---

## 📌 Project Overview

FOOD4NEED allows donors to donate surplus food, NGOs to view and collect donations, and administrators to manage users and approvals.  
It ensures proper coordination so that excess food reaches people in need.

---

## ✨ Features

- 👤 Multiple user roles: Donor, NGO, Admin  
- 🔐 Secure login and authentication  
- 📝 Food donation posting by donors  
- 🏢 NGO dashboard to view available donations  
- ✅ Admin approval system for users  
- 📊 Admin dashboard with donation statistics  

---

## 🛠️ Technologies Used

- **Backend**: Python, Django  
- **Frontend**: HTML, CSS, Bootstrap  
- **Database**: SQLite  
- **Authentication**: Django Authentication System  

---

## 🚀 How to Install and Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/shessy-06/FOOD4NEED.git
cd FOOD4NEED
2️⃣ Create Virtual Environment
python -m venv env

Windows

env\Scripts\activate


Mac / Linux

source env/bin/activate
3️⃣ Install Required Packages
pip install -r requirements.txt

4️⃣ Apply Database Migrations
python manage.py makemigrations
python manage.py migrate

5️⃣ Create Admin User
python manage.py createsuperuser

7️⃣ Open in Browser

Main site:

http://127.0.0.1:8000/
