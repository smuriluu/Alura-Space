# 🪐 Alura Space
## 🐍 Django Project: Templates and Best Practices

This repository contains the project developed during the course **"Django: templates and best practices"**, which teaches how to work with the Django framework in a practical way while following best practices.

## 🏫 About the Course

The course covers:

- How Django works in practice.
- Creating and managing environment variables using Python.
- Using templates and rendering pages with Django.
- Best programming practices for Django projects.
- Developing web applications using Python.

## 📚 Course Content

The project was developed in stages based on the following content:

1. **Starting the application and running the server**  
   Learned how to set up the development environment and run a Django server.

2. **Project, app, and views**  
   Structuring a Django project, creating apps, and configuring views.

3. **Static files**  
   Managing static files like images, CSS, and JavaScript.

4. **Best practices and partials**  
   Applying best practices in development and using partials to reuse code in templates.

## ⚙️ Technologies Used

- **Python**  
- **Django**  
- **HTML** and **CSS** (in templates)

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/project-name.git
   cd project-name
   ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate     # For Windows
    ```

3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the migrations:
    ```bash
    python manage.py migrate
    ```

5. Start the server:
    ```bash
    python manage.py runserver
    Access the project at: http://localhost:8000
    ```
## 📂 Project Structure
```plaintext
├── galeria/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── setup/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── static/
│   ├── admin/
│   ├── assets/
│   └── styles/
├── templates/
│   └── galeria/
│       ├── partials/
│       │   ├── _footer.html
│       │   ├── _menu.html
│       ├── base.html
│       ├── imagem.html
│       └── index.html
├── .env
├── .gitignore
├── db.sqlite3
├── manage.py
├── README.md
└── requirements.txt
```

## 🌟 Lessons Learned
During the development of this project, it was possible to:
- Properly structure Django applications.
- Work with templates and partials to create dynamic layouts.
- Implement development best practices to improve code maintainability.

## Course provided by [Alura](https://cursos.alura.com.br/dashboard)