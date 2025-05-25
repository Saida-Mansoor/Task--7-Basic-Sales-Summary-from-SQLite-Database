# 📊 Task 7: Basic Sales Summary from SQLite Database using Python

## 🧾 Objective

This project demonstrates how to use **SQL inside Python** to extract and visualize basic sales information such as:

* **Total quantity sold per product**
* **Total revenue per product**

It uses a **tiny SQLite database**, Python libraries (`sqlite3`, `pandas`, `matplotlib`), and produces a simple **bar chart** for revenue comparison.

---

## 🧰 Tools Used

* Python 3.x
* SQLite (via `sqlite3`, built-in)
* Pandas
* Matplotlib
* Jupyter Notebook
---

## 📂 Project Structure

1. **Create SQLite Database** (`sales_data.db`)
2. **Create a Sales Table** with fields: `product_name`, `quantity`, `price`
3. **Insert Sample Data**
4. **Run SQL Query** to calculate:

   * Total quantity sold
   * Total revenue (quantity × price)
5. **Load results into Pandas DataFrame**
6. **Print and Plot** results as a bar chart

---

## 📈 Output

* A printed DataFrame showing total quantity and revenue per product
* A bar chart saved as `sales_chart.png`

---

## ▶️ How to Run

1. Run the script or notebook.
2. It will:

   * Create a database (if not already present)
   * Insert sample records
   * Query the summary
   * Show and save a bar chart of revenue

---

## 📸 Example Output

**Printed Table**

```
   product     total_qty     revenue
0  Product A         10         100.0
1  Product B          5         100.0
2  Product C          2         100.0
```

**Bar Chart**

* X-axis: Product Names
* Y-axis: Revenue

---

## ✅ Status

✔️ Completed and Functional
💡 Optional enhancements: Accept user input, export to Excel, or build a GUI version.

---
