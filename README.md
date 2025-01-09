# E-Commerce Website

## Project Overview

This is an eCommerce website built with **Django**, **HTML**, **CSS**, **Bootstrap**, **JavaScript**, and **AJAX**. The platform allows users to browse products, register, log in, manage their profiles, add products to their cart, and complete purchases. The website features responsive design, user authentication, and a dynamic shopping experience.

## Features

### User Authentication:
- Register and log in with email/password.
- Password reset functionality.

### Product Catalog:
- Display a variety of products with prices and descriptions.
- Users can filter products based on categories.

### Shopping Cart:
- Add/remove products to/from the cart.
- View cart details and total cost.

### User Profile:
- Users can view and edit their profiles.
- Order history display for logged-in users.

### Checkout Process:
- Users can view their cart, provide shipping information, and complete orders.

### Responsive Design:
- Optimized for mobile and desktop using **Bootstrap**.

### AJAX Integration:
- Dynamic updates on the cart and product pages without page reload.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, Bootstrap, JavaScript, AJAX
- **Database**: SQLite (or other, if applicable)
- **Version Control**: Git, GitHub

## Installation Instructions

Follow these steps to set up the project on your local machine.

### Prerequisites

- Python 3.x
- Django
- Git

### Steps to Install

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    cd your-repository-name
    ```

2. Create a virtual environment (recommended):

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

5. Create a superuser (to access the Django admin interface):

    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

7. Open your browser and go to `http://127.0.0.1:8000/` to view the website.


## Usage

- To start using the website, simply navigate to the homepage at `http://127.0.0.1:8000/`.
- Register a new account or log in to an existing account.
- Browse products, add items to your cart, and complete a purchase through the checkout process.

## Future Improvements

- Implement payment gateway (e.g., Stripe, PayPal) for real-world transactions.
- Improve product search functionality with filters and search bar.
- Add product recommendations based on user history or popular items.
- Integrate email notifications for order confirmations and status updates.

## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the repository.
2. Clone your forked repository.
3. Create a new branch for your feature or bugfix (`git checkout -b feature-xyz`).
4. Make your changes.
5. Commit your changes with a clear message (`git commit -m "Add feature xyz"`).
6. Push your branch to your forked repository (`git push origin feature-xyz`).
7. Create a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Demo Video

Here is a demo video of the eCommerce website in action:

[![Watch the video]

https://github.com/user-attachments/assets/b03d0ce7-0cd8-48ec-8538-8234aa37ef2f








