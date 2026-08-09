# GPay Expense Sharing Project

## 📌 Project Overview

This project is a **Python program** that helps friends **split and manage shared expenses**.
It calculates how much each person **paid**, **owes**, and who should **pay whom** to settle the expenses.

This is similar to apps like **Splitwise**, but implemented using **Python, NumPy, and PrettyTable**.

---

## ⚙️ Technologies Used

* Python
* NumPy
* PrettyTable

---

## 📂 Project Features

* Add expenses paid by friends
* Automatically split expenses among people
* Calculate each person's balance
* Display settlement in a table
* Suggest who should pay whom to clear debts

---

## 👥 Example Friends

The program tracks expenses between:

* Rajesh
* James
* Aravind
* Harish

---

## 🧮 How It Works

1. A friend pays an amount.
2. The expense is shared among selected friends.
3. The program stores the data in an **expense matrix**.
4. It calculates:

   * Total paid
   * Total owed
   * Final balance
5. It suggests payments to settle the balance.

---

## ▶️ Example Expenses

Example:

* Rajesh paid **₹1250** for Rajesh, James, and Aravind
* James paid **₹800** for James and Aravind

The program then calculates the final settlements.

---

## 📊 Output

The program displays:

* Each person's balance
* Who should pay whom to settle the expenses

Example output:

```
James should pay Rajesh ₹200
Aravind should pay Rajesh ₹150
```

---

## 🚀 How to Run the Project

1. Install required libraries:

```
pip install numpy prettytable
```

2. Run the Python script or Jupyter Notebook.

---

## 📖 Purpose

This project is useful for learning:

* Python programming
* NumPy arrays
* Expense splitting algorithms
* Basic financial calculations

---

## 👨‍💻 Author

Harish.B
