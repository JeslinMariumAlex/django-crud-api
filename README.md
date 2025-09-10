# 📝 Django CRUD API (Notes)

A simple **Django REST Framework API** that supports **CRUD operations** for notes (title + description).  
Built for learning and practice.

---

## 🚀 Features
- Create a new note (POST)  
- Get all notes / single note (GET)  
- Update a note (PUT/PATCH)  
- Delete a note (DELETE)  
- Django REST Framework browsable API  

---

## 🛠 Tech Stack
- **Backend:** Django, Django REST Framework  
- **Database:** SQLite (default, easy for testing)  
- **Tools:** Postman / Django Browsable API for testing  

---

## ⚡ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/YOUR-USERNAME/django-crud-api.git
cd django-crud-api
```

### 2. Create Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
```

### 3. Install Dependencies
```bash
Copy code
pip install -r requirements.txt
```

### 4. Run Migrations
```bash
Copy code
python manage.py makemigrations
python manage.py migrate
```

### 5. Start Development Server
```bash
Copy code
python manage.py runserver
Server will start at 👉 http://127.0.0.1:8000/
```
## 📡 API Endpoints
Method	Endpoint	Description
GET	/api/notes/	List all notes
GET	/api/notes/{id}/	Retrieve note by ID
POST	/api/notes/	Create new note
PUT	/api/notes/{id}/	Update note
PATCH	/api/notes/{id}/	Partial update
DELETE	/api/notes/{id}/	Delete note

## 🧪 Testing the API
Open browser at: http://127.0.0.1:8000/api/notes/

Or use Postman / cURL to send requests.


## ✍️ Author: Jeslin Marium Alex