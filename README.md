# Simple Login Page with Password Validation and Admin Panel

This project is a web-based **login system** built using **HTML** designed for user authentication and role-based behavior (user vs admin). It includes basic password validation, toggle visibility, user feedback, and a minimal admin panel to view all registered demo users.

##  Project Structure

This is a single-page HTML application that contains:

- **Login Form** with:
  - Username/email field
  - Password field with show/hide toggle
  - Validation feedback for minimum input requirements
  - "Forgot Password" alert

- **Welcome Page** for regular users after successful login

- **Admin Panel** with a table of all user credentials (for demo purposes only)

##  Features

-  **Client-side input validation**:
  - Username must be at least 3 characters
  - Password must be at least 6 characters
  - Error messages appear inline

-  **Show/Hide password** toggle for better UX

   **Role-based login behavior**:
  - Regular users are directed to a welcome screen
  - Admin users are shown a table of all users

-  **Demo accounts only** (no server or real database;)

## Demo Users

| Username  | Password   | Role     |
|-----------|------------|----------|
| admin     | admin123   | Admin    |
| user1     | password1  | Regular  |
| user2     | password2  | Regular  |
| testuser  | testpass   | Regular  |

##  Disclaimer

>  This project is a **conceptual prototype** intended for **educational and demonstration purposes only**.  
>
> - It is **not fully tested** or secured for real-world use.  
> - All usernames and passwords are **hard-coded directly in the HTML/JavaScript file** and can be easily accessed or modified.  
> - There is **no encryption**, **no database**, and **no server-side validation**.  
> - Do **not** use this project to manage real user data or deploy it in a production environment.  
>
> This example is designed to illustrate **basic front-end form validation and interface design**, not secure authentication.


## How to Run

### Option 1: Open Directly in Browser

1. Download or clone the repo.
2. Double-click `Password_checker.html` (or right-click > Open With > your browser).

### Option 2: Use Live Server (recommended)

1. Install Live Server globally:
   ```bash
   npm install -g live-server
