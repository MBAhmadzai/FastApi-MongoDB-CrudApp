# 🚀 FastAPI MongoDB CRUD App

A powerful and scalable CRUD (Create, Read, Update, Delete) application built using **FastAPI** and **MongoDB**.

---

## 🔧 Features
- ✅ **FastAPI** – High-performance Python web framework
- ✅ **MongoDB** – NoSQL database for flexible data storage
- ✅ **CRUD Operations** – Create, Read, Update, and Delete functionality
- ✅ **Pydantic Models** – Data validation and serialization
- ✅ **Asynchronous Support** – Optimized for high performance

---

## 📂 Project Structure
```
/fastapi-mongodb-crudapp-master
│── app/
│   ├── main.py        # FastAPI entry point
│   ├── models.py      # Pydantic data models
│   ├── routes.py      # CRUD API routes
│   ├── database.py    # MongoDB connection setup
│── requirements.txt   # Dependencies
│── README.md          # Project documentation
```

---

## 🛠 Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/fastapi-mongodb-crudapp-master.git
   cd fastapi-mongodb-crudapp-master
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run MongoDB** (Ensure MongoDB is running locally or use a cloud database)

5. **Start the FastAPI Server**
   ```bash
   uvicorn app.main:app --reload
   ```
   Open **[http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs)** for interactive API documentation.

---

## 📌 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST   | `/items/` | Create a new item |
| GET    | `/items/` | Retrieve all items |
| GET    | `/items/{id}` | Retrieve a single item by ID |
| PUT    | `/items/{id}` | Update an existing item |
| DELETE | `/items/{id}` | Delete an item |

---
