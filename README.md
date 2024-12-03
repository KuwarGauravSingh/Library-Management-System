
# Django-based Library Management

#### Django Library Management is a web application built with Django, Razorpay, and Tailwind CSS, providing an efficient platform for managing library operations.

---

## Installation 📦
### To set up Django Library Management, follow these steps:

1. Clone this repository:
   ```bash
   'https://github.com/KuwarGauravSingh/Library-Management-System.git'
   ```

2. Navigate to the project directory:
   ```bash
   cd Django-librarymanagement
   ```

3. Create a virtual environment:
   ```bash
   python -m venv env
   ```

4. Activate the virtual environment:
   ```bash
   env\Scripts\activate
   ```

5. Install the project dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Run the server:
   ```bash
   python manage.py runserver
   ```

7. Open your browser and go to `http://localhost:8000`

---

## Features of this Project:

### General Features:
1. View all books on the homepage.
2. Search books by author, title, or category.
3. Sort books or authors alphabetically.

### Student Features:
1. Sign up and log in.
2. Request books.
3. View their book issues and filter by:
   - Requested issues
   - Issued books
   - All records
4. Check fines and view:
   - Remaining days to return a book, or
   - Days overdue for a book.
5. Pay fines online via Razorpay.

### Admin Features:
1. Access an admin dashboard.
2. Manage book issues:
   - View, delete, search by student ID.
   - Filter issues by status (issued, returned).
3. Approve book requests manually or with auto-calculated return dates.
4. Manage books:
   - Add, delete, search, and filter by author.
5. Manage authors: Add, delete, and search.
6. Calculate fines with a click, and manage fines (add, delete, mark paid).
7. Manage students:
   - Add, delete, search, filter by department.
   - View all fines and issues for a specific student.
8. View user details, such as last login and associated student.
9. Reset passwords for any user.

### Additional Features:
1. Real-time validation during sign-up to ensure student ID uniqueness.
2. Logged-in students see real-time book statuses: `Issued`, `Request Pending`, or `Available`.

---

## Usage:
1. Run the server:
   ```bash
   python manage.py runserver
   ```
2. Open `http://localhost:8000` in your web browser.
3. Sign up or log in.
4. Add books to the library.
5. Borrow and return books as needed.
6. Make online payments via Razorpay.

---

## Contributing 💡

Contributions are welcome! To contribute:
1. **Option 1**: 🍴 Fork this repo.
2. **Option 2**: 👯 Clone this repo locally.
3. Build your code 🔨.
4. 🔃 Submit a pull request.

---

## Credits:

Django Library Management was created by **Kuwar Gaurav Singh**.
