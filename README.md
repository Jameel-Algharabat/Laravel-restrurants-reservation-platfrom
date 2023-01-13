# Overview

We developed this project using Laravel, HTML5, CSS3, and JS. Our website aims to provide customers with the best restaurant reservation experience, saving them time and effort. This concept is perfect for scheduling business meetings or family gatherings as it allows customers to choose the day, number of tables, and view the menu on our website, allowing them to also order food online. This way, everything will be ready at the exact time they need it. The site includes:


- A landing page displaying details, staff directory, and YouTube API documentation.
- A user profile section
- The contracts page, which includes all contracts approved by the administrator.
- Each contract has two buttons: contract details and company details. Clicking on them will open a pop-up displaying the details.
- Finally, an error page for when an invalid link is added.


# Setup Guide

- Clone the repository to your local machine
```
git clone https://github.com/Jameel-Algharabat/Laravel-restrurants-reservation-platfrom.git
```
- Navigate to the project directory
```
cd restaurant-reservation-system
```
- Install dependencies
```
composer install
```
- Create a new database and update your .env file with the database credentials.
- Run the migration and seed command
```
php artisan migrate --seed
```
- Start the development server
```
php artisan serve
```
- Open http://localhost:8000 in your browser to view the website


# Technologies Used
- Laravel
- HTML5
- CSS3
- JavaScript

# Disclaimer
Please note that this project is not production ready and has been built for educational purposes only. It may contain bugs or lack certain features and security measures that are required for a production environment. Use it at your own risk.
