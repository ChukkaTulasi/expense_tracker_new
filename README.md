# 💰 Expense Tracker App

A simple and interactive **Expense Tracker** built with **HTML, CSS, and JavaScript** to help users track their daily expenses by category, amount, and date.

---

## 📌 Features

- Add expenses with:
  - **Category** (Food, Rent, Transport, Relaxing)
  - **Amount**
  - **Date**
- View all added expenses in a tabular format
- Automatically calculates and displays the **total amount**
- Delete individual expense entries
- Basic validation for inputs

---

## 🛠 Technologies Used

- **HTML5** – For structuring the web page
- **CSS3** – For styling the interface
- **JavaScript** – For adding functionality (add/delete/update)

---

## 🧾 File Structure
expense-tracker/
│
├── index.html # Main structure of the web app
├── style.css # Styles for layout and design
├── script.js # Logic for expense tracking
└── README.md # Project documentation

---

## 🧠 How It Works

1. User selects a **category**, enters an **amount** and selects a **date**.
2. On clicking **"Add"**, the data is validated and shown in a table.
3. Each expense row includes a **Delete** button.
4. Clicking **Delete** removes the row and updates the total.
5. Total expenses are recalculated and displayed at the bottom.

---

## 🚀 Getting Started

### ✅ Run Locally

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Start tracking your expenses!

---

## 🐞 Known Issues

- Typo in ID: `expnese-table-body` should be corrected to `expense-table-body` in both `HTML` and `JavaScript`.
- Typo in alert: "Please enter a valid amoun" should be "amount".
- Typo in JS function: `inserRow()` should be `insertRow()`.

---

## ✅ Improvements To Make

- Store expenses in `localStorage` for persistence
- Filter by category or date range
- Add charts for visualization (e.g., pie or bar chart)
- Responsive design for mobile view
- Export to CSV or PDF

---

## 🙋 About Me

I'm **Chukka Tulasi Reddy**, an aspiring web developer passionate about building simple and useful applications. This project is part of my learning journey in front-end development.

---

> Built with ❤️ using HTML, CSS & JavaScript
