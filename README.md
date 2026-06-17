# Car Rental Management System

## 📌 Description
A console-based Car Rental Management System built in C++ that manages car rentals, returns, customers, and staff operations with file handling and role-based authentication.

---

## 🚀 Features
- Owner, Customer, and Staff login system (password protected)
- Add and remove cars (Owner)
- View available cars
- Book cars with rental duration
- Return cars with late fee calculation
- Rental history tracking
- File saving and loading (persistent data)
- Password hidden input for security

---

## 👥 User Roles

### Owner
- Add new cars
- Remove cars
- View all available cars
- View rental history

### Customer
- View available cars
- Book a car

### Staff
- Return cars
- View rental history

---

## 🛠️ Technologies Used
- C++
- File Handling (fstream)
- Structs
- Arrays
- Console I/O
- Time functions (ctime)
- Password masking (_getch)

---

## ⚙️ How It Works
1. System starts and loads saved data from files.
2. User selects role (Owner / Customer / Staff).
3. Password verification is required.
4. Operations are performed based on role permissions.
5. All data is saved before exit.

---

## 💾 Data Storage
- `cars.txt` → stores car information
- `rentals.txt` → stores rental history

---

## 📊 Concepts Demonstrated
- Procedural programming in C++
- File persistence
- Authentication system
- Data structures (structs & arrays)
- Time-based calculations (late fees)

---

## 👨‍💻 Author
Youssef Reda
