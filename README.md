# 📦 Django Marketplace Project

A simple Django-based marketplace where users can buy and sell products.

## 🚀 Features
- User authentication (login/register)
- Product listings with images and descriptions
- Secure checkout process

## 🛠 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/steperroX/Django-Marketplace-Project.git
2. Navigate to the project directory:
   ```bash
   cd Django-Marketplace-Project
3. Create and activate a virtual environment
   python -m venv env
   source env/bin/activate  # macOS/Linux
   env\Scripts\activate  # Windows

4. Install dependecies
    ```bash
   pip install -r requirements.txt
5. Apply database migrations
    ```bash
   python manage.py migrate
6. Create a super user (optional, for admin access)
    ```bash
     python manage.py createsuperuser
7. Start the development server
   ```bash
   python manage.py runserver
8. Open the project in your browser
```bash
   http://127.0.0.1:8000/
