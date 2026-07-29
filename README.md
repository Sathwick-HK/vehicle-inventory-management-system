# 🚗 Vehicle Inventory Management System – REST API

A production-style backend REST API built using **Python**, **Django**, and **Django REST Framework**, deployed on **Microsoft Azure App Service** with **Azure Database for PostgreSQL** and automated **GitHub Actions CI/CD**.

This project demonstrates backend development, REST API design, cloud deployment, and database integration.

---

## 🚀 Live API

Base URL

```
https://vehicle-inventory-api-sathwickhk-fgbnbud3egerdcb8.centralindia-01.azurewebsites.net
```

Example Endpoint

```
GET /api/vehicles/
```

---

## ✨ Features

- Create vehicles
- Retrieve all vehicles
- Retrieve vehicle by ID
- Update vehicle details
- Delete vehicles
- JSON REST API
- Django ORM
- Azure PostgreSQL database
- Production deployment on Azure App Service
- GitHub Actions CI/CD
- WhiteNoise static file handling
- Environment variable configuration

---

## 🛠 Tech Stack

### Backend

- Python 3
- Django
- Django REST Framework

### Database

- Azure Database for PostgreSQL Flexible Server

### Cloud

- Azure App Service (Linux)

### Deployment

- GitHub Actions
- Azure Login Action
- Gunicorn
- WhiteNoise

### Version Control

- Git
- GitHub

---

## 📂 Project Structure

```
vehicle-inventory-management-system/

├── manage.py
├── requirements.txt
├── .github/
│   └── workflows/
├── vehicle_inventory/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── vehicles/
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   ├── urls.py
│   └── migrations/
└── README.md
```

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/vehicles/` | List all vehicles |
| POST | `/api/vehicles/` | Create vehicle |
| GET | `/api/vehicles/<id>/` | Retrieve vehicle |
| PUT | `/api/vehicles/<id>/` | Update vehicle |
| DELETE | `/api/vehicles/<id>/` | Delete vehicle |

---

## 🚘 Vehicle Schema

```json
{
    "brand": "Skoda",
    "model": "Slavia Prestige 1.5 TSI DSG",
    "manufacturing_year": 2026,
    "price": "1804000.00"
}
```

---

## ⚙️ Local Setup

Clone the repository

```bash
git clone https://github.com/Sathwick-HK/vehicle-inventory-management-system.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run migrations

```bash
python manage.py migrate
```

Start development server

```bash
python manage.py runserver
```

---

## ☁️ Azure Deployment

The application is deployed using:

- Azure App Service
- Azure Database for PostgreSQL
- GitHub Actions CI/CD
- Gunicorn
- WhiteNoise

Deployment is triggered automatically on every push to the `main` branch.

---

## ✅ Tested Functionality

- Create Vehicle (POST)
- List Vehicles (GET)
- Retrieve Vehicle (GET by ID)
- Update Vehicle (PUT)
- Delete Vehicle (DELETE)

All CRUD operations have been successfully verified against Azure PostgreSQL.

---

## 🎯 Learning Outcomes

This project demonstrates experience with:

- Django
- Django REST Framework
- REST API development
- PostgreSQL
- Azure App Service
- Azure Database for PostgreSQL
- GitHub Actions
- CI/CD pipelines
- Production deployment
- Environment variables
- Gunicorn
- WhiteNoise

---

## 📌 Future Enhancements

- JWT Authentication
- Swagger / OpenAPI Documentation
- Search & Filtering
- Pagination
- Health Check Endpoint
- Automated API Tests
- Docker Support
- Azure Monitor & Application Insights

---

## 👨‍💻 Author

**Sathwick Kashyap**

GitHub:
https://github.com/Sathwick-HK