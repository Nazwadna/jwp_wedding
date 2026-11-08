# Jewepe Wedding Organizer

Web application for **Jewepe**, a wedding organizer, built with **CodeIgniter 3**, PHP, and MySQL.
Customers can browse wedding packages and place orders, while the admin manages the catalog and incoming orders.

## Features

**Customer pages**
- Home page with the wedding package catalog
- Package detail page and order form
- Contact page

**Admin panel**
- Login and dashboard
- Manage wedding packages (add, edit, delete)
- Manage orders and order status
- Order report
- Website settings

## Tech Stack

PHP, CodeIgniter 3, MySQL, HTML, CSS, JavaScript, Bootstrap

## Run Locally

1. Copy the project into your web server folder (for example `htdocs` in XAMPP).
2. Create a MySQL database named `db_wedding_jwp1` with the tables `tb_catalogues`, `tb_order`, and `tb_settings`.
3. Copy `.env.example` to `.env` and fill in the database settings.
4. Open http://localhost/jwp_wedding in the browser.
