# ======================================================================
# BOOKSTORE ANALYZER - README
# ======================================================================

An object-oriented Python command-line application designed for managing 
bookstore inventory, processing purchases, tracking sales, and generating 
visual analytics using `pandas`, `matplotlib`, and `seaborn`.

---

## 🚀 FEATURES

* **Object-Oriented Architecture**: Implements an abstract base class 
  (`AbstractBookStore`) to enforce a strict blueprint for core bookstore operations.
* **Inventory Management**: Add new books with validation checks for positive 
  pricing and quantities.
* **Dynamic Updates & Deletion**: Update stock levels or completely remove books 
  from the inventory dynamically through interactive CLI prompts.
* **Purchase Simulation (`buy_book`)**: Allows users to buy books, check real-time 
  stock availability, and automatically log transaction details.
* **Sales Analytics & Statistics (`record_sale`)**: Uses `pandas` to generate 
  descriptive statistical summaries and group sales data by book titles.
* **Rich Data Visualization (`generate_report`)**: 
  * **Inventory Reports**: Renders bar charts, pie charts (stock distribution), 
    and scatter plots (price vs. quantity relationship).
  * **Sales Visualizers**: Displays sales volume charts, revenue bar plots (`seaborn`), 
    and correlation heatmaps.

---

## 🛠️ PREREQUISITES & DEPENDENCIES

Ensure you have Python installed along with the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
