# Little Lemon Bistro Website

## Project Overview

This project was developed as part of the Meta Backend Developer certification. The primary goal was to build a functional web application for a local neighborhood bistro, Little Lemon, emphasizing their digital presence through a comprehensive menu system. The project required the creation of two main pages:

- **Menu Page**: Showcases the bistro's offerings with categorization.
- **Menu Item Page**: Provides detailed descriptions of each menu item.

### Scenario

Owned by Mario and Adrian, Little Lemon aims to offer the best dining experience both on-site and online. Recognizing the importance of a digital presence, they sought to enhance their website with a dynamic and user-friendly menu system. My role involved using the Django framework to develop this feature, integrating various components such as views, templates, models, and forms to create a seamless online experience.

## Project Structure

The website comprises five main pages:

1. Home
2. About
3. Booking
4. Menu
5. Menu Item

### Core Files Modified

- `settings.py`
- `urls.py` (app-level)
- `models.py`
- `views.py`
- `admin.py`

### Supporting Files

The project was supported by additional pre-existing code files and assets:

- HTML templates for About, Home, and Booking pages
- CSS for styling
- Static images

## Skills and Technologies Used

- **Django Views**: Crafted functional-based to handle the business logic of the application. This included rendering pages, processing form data, and navigating between different sections of the website efficiently.
- **Database Design and Modeling**: Utilized Django models to define the database schema, creating well-structured database tables for storing menu items and other relevant data.
- **Django Templating Engine**: This powerful feature allowed me to integrate Python logic directly within HTML, enabling the generation of responsive and interactive content based on user requests and database queries. Through template inheritance and tags, I crafted a consistent and modular website layout that could dynamically display data with minimal code repetition.

## Setup and Running the Project

## Get Started

To get the Little Lemon Bistro website project up and running on your local machine, follow these steps:

1. **Clone the Repository**: First, clone the project repository to your local machine using the following command in your terminal:
    ```
    git clone <repository-url>
    ```
2. **Database Migrations**: Ensure your database schema is up to date by applying migrations. This step is usually necessary when you first set up the project or after pulling changes that include model updates:
    ```
    python3 manage.py makemigrations
    python3 manage.py migrate
    ```
    However, for this project, migrations are already up to date.
3. **Run the Server**: Navigate to the project directory and start the Django development server with the command:
    ```
    cd path/to/project
    python3 manage.py runserver
    ```
    The server typically runs at `http://127.0.0.1:8000` by default. Open this URL in your web browser to view the project.
4. **Create Superuser (Optional)**: If you need to create an admin user to access the Django admin interface, run:
    ```
    python3 manage.py createsuperuser
    ```
    and follow the on-screen instructions. A default admin user is already set up for demonstration purposes.
## Things to Keep in Mind
- **Default Admin Access**: You can access the Django admin interface by going to `http://127.0.0.1:8000/admin`. Use the following credentials for the default admin user:
    - Username: `bistroadmin`
    - Password: `lemon@786!`
- **Server Port**: In the event that port 8000 is already in use on your machine, or you wish to use a different port, you can specify an alternative port by appending it to the `runserver` command like so:
    ```
    python3 manage.py runserver 8080
    ```
    Replace `8080` with your preferred port number.

Following these setup steps and keeping the mentioned points in mind will help you smoothly run the Little Lemon Bistro website on your local environment for testing.

