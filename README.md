# Pandas-calories-tracker-for-fat-loss
# Stay750 – Daily Calorie Tracker

Stay750 is a lightweight nutrition tracker built with Python and Pandas to help users stay under a strict daily intake of 750 kilocalories. It's designed for minimal calorie intake, health focus, and nutritional awareness.

---

## Project Overview

This project provides a simple system to track food intake and monitor total calories throughout the day. The user inputs food items, and the system calculates the cumulative calories using real nutritional data from a dataset.

---

## Features

- Uses a real-world nutrition dataset (McDonald's India Menu)
- Accepts partial food names
- Tracks daily food intake
- Calculates total calories consumed
- Alerts user if they approach or exceed 750 kcal

---

## Tools and Libraries

- Python 3
- Pandas
- Google Colab
- CSV dataset

---

## How to Use

1. Upload the dataset (CSV) in Google Colab
2. Run the notebook
3. Use the function:
```python
add_item("food name")
