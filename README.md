# 📚 OpenShelf

**Upload. Download. Borrow. Lend.**

OpenShelf is a **community-driven online & offline library platform** that enables users to share knowledge by uploading PDFs and managing physical book borrowing and lending.

---

***Tech Stack:** Django • PostgreSQL • Celery • Redis • Docker • Tailwind CSS • JavaScript • HTML5

---

## ✨ Key Features

- 📤 Upload PDF books
- 📥 Download books
- 📖 Borrow physical books
- 🤝 Lend books to others
- 🔍 Search & filter books
- 👤 User authentication & profiles
- 📚 Personal library management

---

## 🛠️ Tech Stack

### 🎨 Frontend
- HTML5  
- CSS3  
- Tailwind CSS  
- JavaScript (ES6+)  

### ⚙️ Backend
- Django (Python)  
- Django REST Framework  

### 🗄️ Database
- PostgreSQL  

### 🔐 Authentication
- Django Authentication / JWT  

### ⚡ Background Tasks
- Celery  
- Redis  

### 🐳 DevOps
- Docker  
- Docker Compose  

### 🔧 Tools & Version Control
- Git  
- GitHub

---

## 📸 Screenshots

---

## ⚙️ Installation & Setup

```bash
# Clone repository
git clone https://github.com/yourusername/openshelf.git

# Move into project
cd openshelf

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install backend dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Start server
python manage.py runserver
