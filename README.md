# 🧾 Sales Summary using SQLite and Python (Jupyter Notebook)

This project demonstrates how to use **Python** with **SQLite**, **Pandas**, and **Matplotlib** to analyze basic sales data and visualize it — all within a Jupyter Notebook.

---

## 🎯 Objective

- Connect to a small SQLite database (`sales_data.db`)
- Run SQL queries to calculate:
  - Total quantity sold per product
  - Total revenue per product
- Display results with:
  - `print()` for a quick view
  - `matplotlib` bar chart for visual summary

---

## 📒 Tools & Libraries

- Python (Jupyter Notebook)
- `sqlite3` (Built-in)
- `pandas`
- `matplotlib`

---

## 📁 Project Structure

sales_summary_project/├── Sales_Summary.ipynb # Jupyter notebook (main file) └── sales_chart.png # Revenue bar chart


---

## 🚀 How to Run

1. Clone or download this repository.

2. Install dependencies:

   ```bash
   pip install pandas matplotlib
3. Open the notebook:

    jupyter notebook Sales_Summary.ipynb
Run all the cells to:

4. Generate the database (if it doesn't exist)

   Run SQL queries

   Display printed summary

   Show and save a bar chart as sales_chart.png

---
## 📊 Sample Output

--- Basic Sales Summary ---
    product  total_quantity  total_revenue
0    Laptop               3         3550.0
1   Monitor               4         1200.0
2  Keyboard               3          225.0
3     Mouse               7          170.0

## 📈 Bar Chart
A bar chart showing Revenue by Product is generated and saved as sales_chart.png.

---
👨‍💻 Author
Pranathi

GitHub: PRANATHI08D
