# ☕ Coffee Machine – Python OOP

A command-line simulation of a coffee vending machine, built in Python using Object-Oriented Programming. The machine handles drink selection, ingredient tracking, and coin-based payments.

---

## 📖 Project Overview

A fully functional coffee machine simulator split across multiple classes, each responsible for a single aspect of the machine — menu management, resource tracking, and payment processing. The project demonstrates clean OOP design with separation of concerns.

---

## 🚀 Key Features

- ☕ **3 drinks available** – Espresso, Latte, Cappuccino
- 💰 **Coin payment system** – quarters, dimes, nickels, pennies with change calculation
- 📦 **Resource tracking** – water, milk, coffee levels decrease with each order
- 📊 **Admin report** – view current resources and total profit
- 🔒 **Insufficient funds & ingredients handling** – clear error messages and refunds
- 🔄 **Continuous operation** – machine stays on until `off` command

---

## 🎮 How to Use

1. Run the script – the machine prompts for a drink choice
2. Type a drink name: `espresso`, `latte` or `cappuccino`
3. Insert coins when prompted
4. Receive your drink and change ☕

**Special commands:**
| Command | Action |
|---------|--------|
| `report` | Shows current resources and profit |
| `off` | Turns the machine off |

---

## 🛠️ Technologies Used

- **Python 3** – core logic
- **OOP** – 4 separate classes with single responsibilities

No external libraries required.

---

## 📂 Project Structure

```
/Coffee-machine_OOP
├── main.py           # Entry point – main game loop
├── menu.py           # Menu and MenuItem classes – drink definitions
├── coffee_maker.py   # CoffeeMaker class – resource and brewing logic
├── money_machine.py  # MoneyMachine class – payment processing
└── README.md
```

---

## ▶️ How to Run

```bash
git clone https://github.com/PawelK123/Coffee-machine_OOP.git
cd Coffee-machine_OOP
python main.py
```

---

## 🧠 OOP Structure

| Class | Responsibility |
|-------|---------------|
| `Menu` | Stores available drinks and handles search |
| `MenuItem` | Represents a single drink with ingredients and cost |
| `CoffeeMaker` | Tracks resources, checks availability, brews coffee |
| `MoneyMachine` | Handles coin input, calculates change, tracks profit |

---

