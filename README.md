# 📝 Blog Application

A feature-rich **Blog Application** built with **Django** that allows users to create, read, update, and delete (CRUD) blog posts. This application also supports user authentication, post categorization, and a clean, responsive design.

## 🚀 Features

- ✅ **User Authentication**: Secure registration, login, and logout
- ✅ **CRUD Functionality**: Create, Read, Update, and Delete blog posts
- ✅ **Post Categorization**: Organize posts by categories
- ✅ **Search Functionality**: Search blog posts by title or content
- ✅ **Responsive Design**: Seamlessly adapts to all screen sizes
- ✅ **Admin Dashboard**: Manage posts and categories with Django admin

## 🛠️ Tech Stack

- **Framework**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default) or PostgreSQL
- **Version Control**: Git & GitHub

## 📂 Project Structure

```
blog-application/
├── blog/              # Main Django app
│    ├── migrations/   # Database migrations
│    ├── static/       # CSS, JS, images
│    ├── templates/    # HTML templates
│    ├── views.py      # Core logic
│    ├── models.py     # Database models
│    └── urls.py       # URL routes
├── manage.py          # Django management script
└── requirements.txt   # Python dependencies
```

## 📌 Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/blog-application.git
cd blog-application
```

2. **Set Up a Virtual Environment** (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install Dependencies**

```bash
pip install -r requirements.txt
```

4. **Apply Migrations**

```bash
python manage.py migrate
```

5. **Create a Superuser** (Access Admin Dashboard)

```bash
python manage.py createsuperuser
```

6. **Run the Development Server**

```bash
python manage.py runserver
```

Visit **http://localhost:8000/** to access the blog.

## 📚 Usage Guide

- **Home Page**: View the latest blog posts
- **Create Post**: Authenticated users can add new posts
- **Edit/Delete**: Users can update or delete their posts
- **Admin Panel**: Access at `/admin` for post and user management

## 📄 Environment Variables (Optional)

Create a `.env` file in the root directory for sensitive data:

```
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=your_database_url
```

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-name`)
5. Create a Pull Request

## 📜 License

This project is licensed under the **MIT License**. Feel free to use and modify it!

## 📧 Contact

For any inquiries or suggestions, contact me at:

- **GitHub**: [saivivek7881](https://github.com/saivivek7881)
- **Email**: saivivekgundeti7881@gmail.com

---

⭐ If you found this project useful, consider giving it a **star** on GitHub!

