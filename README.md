Video: https://drive.google.com/drive/folders/1IrKiqIdcHVJIUGdE-FDbR2bpOayaaiWf?usp=sharing

# 🎓 Student Management System - Database Course Task1

A simple console application that performs full **CRUD operations** on a Student database, built with **C#** and **PostgreSQL**.

---

## 🛠️ Technologies Used
- C# / .NET 10
- PostgreSQL 18
- Npgsql (PostgreSQL driver for .NET)
- JetBrains Rider

---

## ⚙️ How It Works
The app connects to a local PostgreSQL database called `studentdb` and operates on a `Student` table with the following structure:

| Column | Type | Description |
|--------|------|-------------|
| Id | INTEGER | Auto-generated primary key |
| Name | VARCHAR(100) | Student name (required) |
| Age | INTEGER | Student age |
| GPA | DECIMAL(3,2) | Student GPA |

---

## 🚀 Features
- ➕ **Add** a new student
- 📋 **View** all students
- ✏️ **Update** a student by ID
- 🗑️ **Delete** a student by ID

---

## 🔒 Security Note
All database operations use **parameterized queries** to prevent SQL injection.

---

## 📋 How to Run
1. Make sure PostgreSQL is running
2. Update the connection string in `Program.cs` with your own password
3. Open the project in JetBrains Rider
4. Run the project
