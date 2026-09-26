# BMI Tracker

A simple desktop BMI calculator built with Python, CustomTkinter, and SQLite.

## Features

* Calculate BMI from weight and height
* Display BMI category
* Save BMI calculations to a SQLite database
* View calculation history
* Clear calculation history
* Simple and user-friendly graphical interface

## Technologies

* Python
* CustomTkinter
* SQLite
* `datetime`

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/bmi-tracker.git
```

2. Open the project folder:

```bash
cd bmi-tracker
```

3. Install CustomTkinter:

```bash
pip install customtkinter
```

4. Run the program:

```bash
python main.py
```

## How It Works

Enter your:

* Weight in kilograms
* Height in centimeters

Then click **Calculate**.

The program calculates BMI using the formula:

```text
BMI = weight / (height / 100)²
```

Each calculation is automatically saved to the SQLite database.

## Project Structure

```text
bmi-tracker/
│
├── main.py
├── bmi_history.db
└── README.md
```

The database file is created automatically when the program starts.

## BMI Categories

The program displays a category based on the calculated BMI:

* Below 18.5 — Underweight
* 18.5–24.9 — Normal weight
* 25–29.9 — Overweight
* 30 or above — Obesity

## License

This project is open source and available for learning and personal use.

