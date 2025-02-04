# E-Diary - A Personal Diary Web Application

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Django](https://img.shields.io/badge/Django-3.x-green) ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-purple) ![License](https://img.shields.io/badge/License-Free%20for%20Educational%20Use-orange)

E-Diary is a web-based personal diary application built using Django and Bootstrap. It allows users to register, log in, create categories, and add their thoughts under those categories. This project is designed to help users organize their thoughts and ideas in a structured and secure manner.

---

## Features

- **User Authentication**: Secure registration and login system.
- **Category Management**: Users can create and manage categories for organizing their thoughts.
- **Thought Entries**: Users can add, edit, and delete their thoughts under specific categories.
- **Responsive Design**: Built with Bootstrap for a clean and mobile-friendly user interface.
- **User-Friendly**: Simple and intuitive interface for easy navigation.

---

## Technologies Used

- **Backend**: Python, Django
- **Frontend**: HTML, Bootstrap
- **Database**: SQLite (default Django database)

---

## How to Run the Project

### Prerequisites

Before running the project, ensure you have the following installed:

- **Python** (v3.x or higher)
- **Django** (v3.x or higher)
- **PIP** (for installing Python modules)

### Installation Steps

1. **Download the Source Code**:
   - Clone or download the project repository.

2. **Navigate to the Project Directory**:
   - Open your terminal or command prompt.
   - Change the working directory to the project folder:
     ```bash
     cd path/to/e-diary-project
     ```

3. **Install Required Dependencies**:
   - Run the following command to install Django:
     ```bash
     pip install Django
     ```

4. **Set Up the Database**:
   - Apply migrations to set up the database:
     ```bash
     python manage.py migrate
     ```

5. **Create a Superuser (Optional)**:
   - Create a superuser to access the Django admin panel:
     ```bash
     python manage.py createsuperuser
     ```

6. **Run the Development Server**:
   - Start the Django development server:
     ```bash
     python manage.py runserver
     ```

7. **Access the Application**:
   - Open your web browser and navigate to:
     ```
     http://localhost:8000/ or http://127.0.0.1:8000/
     ```

---

## Project Structure

- **Templates**: Contains HTML files for the frontend.
- **Static**: Includes CSS, JavaScript, and Bootstrap files.
- **Models**: Defines the database structure for categories and thoughts.
- **Views**: Handles the logic for user authentication, category management, and thought entries.
- **URLs**: Manages the routing for the application.

---

## Notes

- This project is for **educational purposes only**.
- Feel free to modify and extend the source code as needed.
- If you encounter any missing modules, install them using `pip`.

---

## License

This project is free to use for educational purposes. The source code is provided as-is, without any warranties.

---

## Acknowledgments

- Developed as a learning project to demonstrate Django's capabilities in building web applications.
- Built with ❤️ using Python, Django, and Bootstrap.
- Developed by **Khandaker Nafisa Tabassum**.
- Submitted on **February 2, 2025**.

---

---

Enjoy using E-Diary to organize your thoughts and ideas! If you have any questions or feedback, feel free to reach out.
