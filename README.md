# learn_BuildingDBApp_SQL-Python
Learned building Database Apps with PostgreSQL and Python

---

## 🙏 Credits
This code is **not original work**. It was written as part of a hands-on coding exercise from the Udemy course:
**[The Ultimate Python Masterclass: Build 24 Python Projects]**(https://www.udemy.com/course/python-masterclass-course/)
by **Ashutosh Pawar**  Software Engineer, Entrepreneur, Python & Django Geek.

The purpose of this repository is solely for:
- Personal learning
- Practicing code structure and concepts
- Reviewing Tkinter and PostgreSQL integration
No modifications have been made to the original source code from the course.
## 🚫 Please Do Not Reuse for Commercial Purposes

If you wish to use this project beyond personal learning, you should take the course and follow its licensing terms.

---

# Student Management GUI with PostgreSQL

This is a Python-based desktop application that provides a **Graphical User Interface (GUI)** to manage student records stored in a **PostgreSQL** database.

The app is built using **Tkinter** and supports full CRUD operations:
- Create Table
- Insert Student Data
- Update Student Data
- Delete Student Data
- View All Records (in a Treeview widget)

---

## Tech Stack

- Python 3.x
- Tkinter (GUI)
- psycopg2 (PostgreSQL adapter)

---

## 🗃️ Database Schema

Table: `students`

| Column      | Type    |
|-------------|---------|
| student_id  | SERIAL PRIMARY KEY |
| name        | TEXT    |
| address     | TEXT    |
| age         | INT     |
| number      | TEXT    |

---

## 🚀 How to Run

1. Make sure PostgreSQL is installed and running.
2. Create a database named `sample`.
3. Open terminal and run:

```bash
python tkinter_sql_gui.py
