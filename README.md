# Student Report Management System (SRMS)

A simple **C-based project** that manages student records using file handling.  
This system supports role-based login and allows different levels of access.

---

## Features

- Login system (Admin, Staff, Guest)
- Add student records (Admin only)
- View all students
- Search student by roll number
- Update student details
- Delete student records (Admin only)
- File-based storage (no database)

---

## User Roles

| Role   | Permissions |
|--------|------------|
| Admin  | Full access (Add, View, Search, Update, Delete) |
| Staff  | View, Search, Update |
| Guest  | View only |

---

## Technologies Used

- C Programming
- File Handling
- Structures
- Conditional Statements

---

## Project Files

- `code.c` - Main program
- `students.txt` - Stores student data
- `credentials-sample.txt` - Sample login credentials
- `srms-report.pdf` - Project documentation

---

## How to Run

```bash
gcc code.c -o srms
./srms
```
---

## Sample Credentials

```bash
admin admin123 ADMIN
staff staff123 STAFF
guest guest123 GUEST
```

---

## Project Description

This project demonstrates the use of **file handling in C** to store and manage student data.  
It implements a **role-based access system**, ensuring secure and controlled operations.

---

## Future Improvements

- Add GUI interface
- Use database instead of text files
- Improve security (password encryption)

---

## Author

Harini K
