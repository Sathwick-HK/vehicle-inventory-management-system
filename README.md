# 🚗 Vehicle Inventory Management System – REST API
### *A Python + Django REST Framework Backend Project*

This project is a fully functional backend API built using **Python**, **Django**, and **Django REST Framework (DRF)**.  
It allows users to manage vehicle inventory through standard **CRUD operations**.

This project is designed for **beginner-to-intermediate Python developers** applying for backend or Python developer roles requiring skills in:

- REST API development  
- Django models, serializers, views, URLs  
- API design & database interaction  
- CRUD operations with Django ORM  

---

## 🌟 Features

- Add new vehicles to inventory  
- Retrieve vehicle list  
- Update vehicle details  
- Delete vehicles  
- JSON-based API responses  
- Uses Django ORM & SQLite  
- Clean and modular app structure  

---

## 🛠 Tech Stack

- **Python 3.x**  
- **Django**  
- **Django REST Framework**  
- **SQLite (default DB, can be replaced with MySQL/PostgreSQL)**  

---

## 📁 Project Structure

```
vehicle-inventory-management-system/
│
├── manage.py
├── README.md
│
├── vehicle_inventory/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
└── vehicles/
    ├── models.py
    ├── serializers.py
    ├── views.py
    ├── urls.py
    └── migrations/
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/vehicles/` | Get all vehicles |
| POST | `/api/vehicles/` | Add a new vehicle |
| GET | `/api/vehicles/<id>/` | Get a vehicle by ID |
| PUT | `/api/vehicles/<id>/` | Update a vehicle |
| DELETE | `/api/vehicles/<id>/` | Delete a vehicle |

---

## 🚙 Vehicle Model

```
brand  
model  
manufacturing_year  
price
```

Example JSON:

```json
{
  "brand": "Honda",
  "model": "Civic",
  "manufacturing_year": 2021,
  "price": 17500
}
```

---

## ⚙️ Setup Instructions (Optional — for users running locally)

```bash
# 1. Install dependencies
pip install django djangorestframework

# 2. Run migrations
python manage.py makemigrations
python manage.py migrate

# 3. Start the server
python manage.py runserver
```

API will be available at:
```
http://127.0.0.1:8000/api/vehicles/
```

---

## 🎯 Purpose of This Project

This project demonstrates:

- Python backend development  
- REST API architecture  
- Clean data modeling  
- CRUD operations  




---

## 📌 Status

This project is part of a learning portfolio and may be expanded with:

- Authentication  
- Pagination  
- Search & filtering  
- Docker support  
- Deployment on Render/Heroku  

---


