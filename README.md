
# 🍽️ Canteen Management System

A simple C-based program to manage canteen operations like menu management, order placement, inventory control, and feedback collection. Developed as part of the course 22AIE101: Problem Solving & C Programming (Fall 2023).

## 📜 Description

This project streamlines day-to-day canteen activities through a console-based interface. It provides administrators and customers with functionalities such as:

- Displaying the menu
- Adding new items
- Refilling stock
- Searching items
- Placing and displaying orders
- Deleting items
- Collecting feedback

Data is stored persistently using `.txt` or `.csv` files.

## 💻 Features

- Display current menu with item details
- Add, delete, or refill food items
- Search food items by name
- Place orders with quantity validation
- Display total order with tax calculation
- Save/load menu from files
- Collect structured feedback from customers

## 🛠️ How to Run

1. Compile the code using any standard C compiler:
   ```bash
   gcc canteen.c -o canteen
   ```

2. Run the executable:
   ```bash
   ./canteen
   ```

3. Follow the console menu options to interact with the system.

## 📁 File Structure

```
canteen/
├── canteen.c             # Main program file
├── menu.txt / menu.csv   # Stores menu items
├── feedback.txt / feedback.csv  # Stores customer feedback
└── README.md             # This file
```

## 👨‍💻 Team Members

- **Shreya Arun** — Menu display, add item, search item, file handling
- **Siri Sanjana S** — Place order, display order, txt file support
- **Varshitha Thilak Kumar** — Refill item, delete item, switch case logic, csv file support

## 📈 Future Improvements

- Add user authentication for admin/customer roles
- Introduce a GUI interface (maybe stop being allergic to front-end)
- Integration with payment gateways
- Real-time inventory sync with databases

## 📄 License

For educational use only.

---

