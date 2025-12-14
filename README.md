# 🎓 Student Management Project

A **Python-based desktop application** built using **Tkinter** and **SQLite** to manage student records, courses, and fee transactions through a simple and interactive graphical user interface.

---

## 📌 Features

* 🔐 Admin login system
* 🧑‍🎓 Student registration with auto-generated ID
* 🔍 Search student records by registration ID
* 💰 Fee deposit and remaining balance tracking
* 📚 Add and update course details
* 🗄 SQLite database for data storage
* 🖥 User-friendly GUI using Tkinter

---

## 🛠 Technologies Used

* **Language:** Python
* **GUI:** Tkinter
* **Database:** SQLite
* **Image Handling:** Pillow (PIL)

---

## 🗂 Database Structure

### Student Table

| Field      | Description             |
| ---------- | ----------------------- |
| Std_ID     | Student Registration ID |
| Std_Name   | Student Name            |
| Std_Mob_No | Mobile Number           |
| Std_Course | Course Name             |
| Course_Fee | Total Course Fee        |
| Balance    | Remaining Fee           |

### Course Table

| Field       | Description |
| ----------- | ----------- |
| Course_Name | Course Name |
| Course_Fee  | Course Fee  |

---

## ▶ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/student-management-project.git
```

2. Navigate to the project directory

```bash
cd student-management-project
```

3. Install required libraries

```bash
pip install pillow
```

4. Run the main file

```bash
python main.py
```

---

## 🔑 Login Credentials

```
Username: admin
Password: admin
```

---

## 📸 Screenshots

### 🔐 Admin Login Screen

![Admin Login](images/Screenshot(8).png)

### 🧭 Admin Dashboard

![Admin Dashboard](Images/Screenshot(9).png)

---

## 🚀 Future Enhancements

* Student update and delete functionality
* Role-based authentication
* Display all students using Treeview
* Export records to Excel or PDF
* Stronger password security

---

## 🙌 Author

**Nishant Dubey** 

GitHub: [@dubeyynishant](https://github.com/dubeyynishant)
