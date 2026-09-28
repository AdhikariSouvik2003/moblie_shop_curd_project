# 📱 Mobile Shop Management System

A simple **Mobile Shop Management System** built using **Python**.

This project is a **CRUD (Create, Read, Update, Delete)** application that allows users to manage mobile phone records.

## 🚀 Features

* ➕ Add a new mobile
* 📋 Display all mobiles
* 🔍 Search a mobile by Mobile ID
* ✏️ Update mobile details
* 🗑️ Delete a mobile
* 🚪 Exit the application

## 🛠️ Technologies Used

* Python 3
* Lists
* Functions
* `for` loop
* `if-else`
* `match-case`
* User input
* CRUD operations

## 📂 Project Structure

```text
Mobile-Shop-Management/
│
├── project.py
└── README.md
```

## 📋 Mobile Information

Each mobile record contains:

| Field     | Description             |
| --------- | ----------------------- |
| Mobile ID | Unique ID of the mobile |
| Brand     | Mobile brand name       |
| Model     | Mobile model            |
| Price     | Price of the mobile     |
| Quantity  | Available quantity      |

## ▶️ How to Run

Make sure Python 3 is installed.

Open the project folder in the terminal and run:

```bash
python project.py
```

## 📌 Main Menu

When you run the program, you will see:

```text
=============================================
       MOBILE SHOP MANAGEMENT
=============================================
1. Add Mobile
2. Display All Mobiles
3. Search Mobile
4. Update Mobile
5. Delete Mobile
6. Exit
=============================================
```

## ➕ Add Mobile

Select option `1` and enter:

```text
Enter Mobile ID:
Enter Brand:
Enter Model:
Enter Price:
Enter Quantity:
```

The program checks whether the Mobile ID already exists before adding the record.

## 📋 Display Mobiles

Select option `2` to display all available mobile records in a table format.

## 🔍 Search Mobile

Select option `3` and enter the Mobile ID.

The program searches the mobile list and displays the matching mobile information.

## ✏️ Update Mobile

Select option `4` and enter the Mobile ID.

You can update:

* Brand
* Model
* Price
* Quantity

## 🗑️ Delete Mobile

Select option `5` and enter the Mobile ID.

The program asks for confirmation before deleting the mobile record:

```text
Do you want to delete this mobile? (Y/N):
```

## 💾 Data Storage

The mobile records are currently stored in a Python list:

```python
mobiles = []
```

Each mobile is stored as:

```python
[mobile_id, brand, model, price, quantity]
```

The data is stored **temporarily in memory**, so records will be lost when the program is closed.

## 👨‍💻 Author

**Souvik Adhikari**

## 📄 License

This project is created for **learning and practice purposes**.
