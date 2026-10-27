# Spin the Wheel Generator

Lab 5 project for **SPG 0473 Web Programming** (HTML, PHP and MySQL).

A visitor types a list of options, picks a colour theme and presses Spin.
PHP picks a random winner and draws a wheel that spins and stops on it.
Wheels and winners can be saved in a MySQL database.

## Team

- Partner A: (name, GitHub username)
- Partner B: (name, GitHub username)
- Class: (class)

## How to run it

1. Install XAMPP and start **Apache** and **MySQL**.
2. Put this folder in `C:\xampp\htdocs\wheel`.
3. Open these pages once, in this order:
   - `http://localhost/wheel/create_db.php`
   - `http://localhost/wheel/create_tables.php`
   - `http://localhost/wheel/insert_samples.php`
4. Start at `http://localhost/wheel/index.html`.

## Files

| Task | Files |
|------|-------|
| 1-2 HTML | `index.html`, `create.html` |
| 3-4 PHP basics | `title.php`, `wheel_lib.php`, `test_lib.php` |
| 5-7 PHP form, wheel, session | `spin.php`, `style.css`, `reset.php` |
| 8-9 MySQL setup | `create_db.php`, `db.php`, `create_tables.php` |
| 10-13 MySQL records | `insert_samples.php`, `save_wheel.php`, `saved.php`, `spin_saved.php`, `update_wheel.php`, `delete_wheel.php` |
