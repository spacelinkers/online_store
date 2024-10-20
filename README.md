# Online Store

A full-featured online shopping platform built with Django. This project allows users to browse products, add items to the cart, and proceed to checkout. It includes essential functionalities like user authentication, product listing, search, and order management.



## Features

- User authentication (Sign Up, Login, Logout)
- Product listing with categories and search functionality
- Cart and checkout system
- Order management for both users and administrators
- Admin panel to manage products, orders, and users

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: PostgreSQL
- **Others**: Django Admin, Django Templates

## Installation and Setup

1. **Clone the repository**:

```bash
git clone https://github.com/spacelinkers/online_store.git
cd online_store
```

2. **Create a virtual environment**:

```bash
python3 -m venv venv
source venv/bin/activate
```
3. **Install the required dependencies**:

```bash
pip install -r requirements.txt
```

4. **Apply migrations**:

```bash
python manage.py migrate
```
5. **Create a superuser (for accessing the admin panel)**:

```bash
python manage.py createsuperuser
```

6. **Run the development server**:

```bash
python manage.py runserver
```

Now the application will be available at http://127.0.0.1:8000/.

## Usage
- **Users**: Users can register, log in, and manage their profiles. They can browse through products, add items to their cart, and complete purchases.
- **Admin**: Admins can manage products, orders, and users from the Django Admin interface (/admin).

## License
This project is licensed under the MIT License.
