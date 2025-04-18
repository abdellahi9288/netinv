# Inventory Management System

A Django-based inventory management system that helps businesses track and manage their inventory efficiently.

## Features

- User authentication and authorization
- Inventory tracking and management
- Transaction history
- Product categorization
- Stock level monitoring
- Admin dashboard

## Installation

1. Clone the repository:
```bash
git clone https://github.com/abdellahi9288/netinv.git
cd netinv
```

2. Create and activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

5. Create a superuser:
```bash
python manage.py createsuperuser
```

6. Run the development server:
```bash
python manage.py runserver
```

7. Access the application at http://127.0.0.1:8000/

## Project Structure

- `core/`: Main project configuration
- `inventory/`: Inventory management app
- `transactions/`: Transaction handling app
- `templates/`: HTML templates
- `static/`: Static files (CSS, JS, images)
- `locale/`: Translation files

## Technologies Used

- Django 3.0.7
- Python
- SQLite
- HTML/CSS
- Bootstrap

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 