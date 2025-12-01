# Complete Django E-commerce Project

This is a **full-featured e-commerce website** built using **Django and Python**. The project allows users to browse products, manage their accounts, add products to cart, and make purchases. Admins can manage products, categories, and user orders via the Django admin panel.

---

## 🛠 Technologies Used

* **Backend:** Django, Python
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite (default)
* **Other:** Pillow (for image handling), Django templates

---

## ⚡ Features

* User registration and authentication
* User profile management with profile image
* Product categories and product listing
* Add products to cart and checkout
* Admin panel to manage products, categories, and orders
* Responsive design for mobile and desktop

---

## 💻 Installation

1. **Clone the repository:**

```bash
git clone https://github.com/sagarchandel930182/complete-django-ecommerce.git
```

2. **Navigate to the project directory:**

```bash
cd complete-django-ecommerce
```

3. **Create a virtual environment (recommended):**

```bash
python -m venv venv
```

4. **Activate the virtual environment:**

* On Windows:

```bash
venv\Scripts\activate
```

* On Linux/Mac:

```bash
source venv/bin/activate
```

5. **Install required packages:**

```bash
python -m pip install -r requirements.txt
```

*(If `requirements.txt` not present, install manually: `python -m pip install django pillow`)*

6. **Apply migrations:**

```bash
python manage.py migrate
```

7. **Run the development server:**

```bash
python manage.py runserver
```

8. **Open in browser:**

```
http://127.0.0.1:8000/
```

---

## 🧑‍💻 Admin Access

Create a superuser to access the Django admin:

```bash
python manage.py createsuperuser
```

Follow prompts to set username, email, and password.
Admin panel URL:

```
http://127.0.0.1:8000/admin/
```

---

## 📦 Project Structure

```
complete-django-ecommerce/
│
├── accounts/          # User accounts, profiles
├── base/              # Utility functions, emails
├── products/          # Product and category models
├── templates/         # HTML templates
├── static/            # CSS, JS, images
├── manage.py
└── requirements.txt
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a branch (`git checkout -b feature-name`)
3. Make changes and commit (`git commit -m "Description"`)
4. Push to branch (`git push origin feature-name`)
5. Create a Pull Request

---

## 📄 License

This project is **open-source** and free to use for learning purposes.

---

## 📧 Contact

**Sagar Chandel**
Email: `sagarchandel930182@gmail.com`
