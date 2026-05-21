# PeakBook — Book Inventory Management System

### 1. Place the project in your web server root
Copy the `peakbook/` folder to:
- **XAMPP**: `C:/xampp/htdocs/peakbook/`

### 2. Create the database
Open **phpMyAdmin** (or MySQL CLI) and run:
```sql
SOURCE /path/to/peakbook/database.sql;
```
Or paste the contents of `database.sql` into phpMyAdmin's SQL tab.

### 3. Configure database credentials
Edit `php/config.php`:
```php
define('DB_HOST', 'localhost');
define('DB_USER', 'root');       
define('DB_PASS', '');           
define('DB_NAME', 'peakbook_db');
```

### 4. Open in browser
Navigate to: `http://localhost/peakbook/`

**Default login** (from seed data):
- Email: `rizz@peakbook.com`
- Password: `password`

---

## Features
- ✅ User Login & Registration (bcrypt password hashing)
- ✅ Dashboard with live stats (total books, customers, income)
- ✅ Weekly income bar chart
- ✅ Full CRUD for: **Books, Customers, Orders, Suppliers, Couriers, Payments**
- ✅ Search / pagination on all tables
- ✅ Add / Edit modal dialogs with smart dropdowns
- ✅ Delete confirmation dialog
- ✅ Toast notifications (success / error)
- ✅ Analysis page with 4 charts
- ✅ Reports page with date range filter and print support
- ✅ Responsive sidebar layout
- ✅ Dark mountain aesthetic matching your Figma design
    
