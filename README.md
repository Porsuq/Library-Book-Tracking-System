# 📚 Library Book Tracking System (C# Console Application)

A simple C# console application designed for managing a small school library. This system allows staff to add books and students, lend and return books, and view records. Data is saved to and loaded from `.txt` files to maintain persistence between sessions.

---

## 🧩 Features

### 📘 Book Management
- Add new books (ISBN, title, author)
- List all books in the library
- Search for books by title or ISBN
- Lend books to students
- Return borrowed books

### 🧑‍🎓 Student Management
- Register new students (ID, first name, last name)
- List all students
- View the books currently borrowed by each student

### 💾 File Storage
- Automatically saves all book and student data to `.txt` files
- Loads saved data when the program starts

---

## 🛠 Technologies Used

- **Language**: C#  
- **Platform**: .NET Framework (Visual Studio 2022)  
- **Data Persistence**: File I/O using `System.IO`  
- **Programming Concepts**:
  - Classes and objects
  - Lists (`List<T>`)
  - Console input/output
  - `if-else`, `foreach`, basic search

---

## 🚀 How to Run

1. **Download or clone** this repository
2. Open the solution file (`.sln`) in **Visual Studio 2022**
3. Build the project (preferably in **Release** mode)
4. Navigate to the output folder:  
   `bin\Release\` or `bin\Debug\`
5. Run `LibraryBookTrackingSystem.exe`

---

## 📦 Release

You can download the latest compiled version as a `.zip` from the [Releases](https://github.com/yourusername/repo-name/releases) section.

---

## ✅ Completed Scope

- Core library management features
- Console-based user interface
- Data stored in plain `.txt` files

> 📝 Advanced features like JSON support, deadlines, and database integration were not included in this version.

---

## 📄 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this project.

---

## 👨‍💻 Author

Developed by Porsuq.  
