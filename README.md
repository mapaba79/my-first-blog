# 📝 My Blog with Django

This is a blog project created following the [Django Girls Tutorial](https://tutorial.djangogirls.org/en/). The goal is to learn the fundamentals of Django and develop a simple web application.

## 🚀 Technologies Used

- **Python** 🐍
- **Django** 🌍
- **SQLite** 📂 (default database)
- **HTML & CSS** 🎨
- **Bootstrap** (for styling)

## 📌 Features

- Create, edit, and delete posts
- Display posts on the homepage
- Django admin panel

## 📦 How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/mapaba79/my-first-blog.git
   cd my-first-blog
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate  # Windows
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the database migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser (optional, for accessing the admin panel):

   ```bash
   python manage.py createsuperuser
   ```

6. Start the local server:

   ```bash
   python manage.py runserver
   ```

7. Access in your browser:

   ```
   http://127.0.0.1:8000/
   ```

## 🎯 Next Steps

- Improve the blog design
- Add image support in posts
- Implement user authentication

## 📜 License

This project is licensed under the MIT License. Feel free to use and modify!

---

Made following the [Django Girls Tutorial](https://tutorial.djangogirls.org/en/)
