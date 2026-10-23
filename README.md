# FullStack Zone

A PHP + MySQL participant-registration web app for a cycling club — built as CET138 Full Stack Development coursework (March 2026).

## Features

- Participant registration form with server-side handling
- Search participants by name/details
- View the full participant list
- Admin login and admin menu
- Edit and delete participant records (admin side)

## Tech

- PHP (server-side pages: `register.php`, `login.php`, `search_result.php`, `edit_participant.php`, `delete.php`, …)
- MySQL database — schema in `cycling.sql`
- HTML front-end forms

## Run it locally

1. Install XAMPP (or any Apache + MySQL + PHP stack) and start Apache and MySQL.
2. Import `cycling.sql` into MySQL (e.g. via phpMyAdmin) to create the database and tables.
3. Copy this folder into your web root (e.g. `htdocs/fullstack-zone`).
4. Check the connection settings in `dbconnect.php` match your local MySQL setup.
5. Open `http://localhost/fullstack-zone/` in a browser.

## Note

Coursework project — written for learning, so it favours clarity over production hardening.
