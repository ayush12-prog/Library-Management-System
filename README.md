📚 Library-Management-System-JFX
A JavaFX-based Library Management System that helps library staff manage books, users, transactions, and fines efficiently. Built with MySQL/SQLite, Hibernate, and Maven, this project enhances skills in database connectivity, exception handling, and UI design.

Project Overview
This project is a Standalone JavaFX application developed as a final project for the JavaFX module. The Library Management System (LMS) streamlines the day-to-day operations of a physical library by digitizing book and user management, borrowing/return tracking, and fine calculation.

🎯 Objectives
Build a user-friendly, functional Library Management System.
Utilize JavaFX for the frontend and MySQL/SQLite for the backend.
Implement full CRUD functionality with JDBC.
Ensure proper form validation, error handling, and reporting.

🧰 Technologies Used

Language	Java
UI Framework	JavaFX with SceneBuilder(JFoenix)
Database	MySQL / SQLite
ORM	Hibernate (optional)
Build Tool	Maven
Reports	JasperReports

📌 Features

🔖 Book Management
Add, update, delete books
Search books by title, author, or genre
View list of all available books.

👥 User Management
Register new users with contact info and membership date
Edit or delete user details
Search users by name or ID

📖 Borrow & Return
Allow users to borrow books (up to 3)
Record return dates and overdue status
Maintain user borrowing history

💸 Fine Management
Automatic fine calculation (e.g., Rs.10 per day overdue)
Allow users to pay fines

📊 Reports
Generate reports for:
All books
Borrowed books
Overdue books and fines

🧱 Database Schema
Books: BookID, ISBN, Title, Author, Categoty, Copies
Members: MemberID, Name, Contact, NIC
Borrowings: BorrowID, MemberID, BookID, IssueDate, ReturnDate, Fine


