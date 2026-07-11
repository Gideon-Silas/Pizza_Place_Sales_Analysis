# Pizza Place Sales Analysis

## Project Overview
This project analyzes a full year of sales data for a fictitious pizza restaurant to discover key operational insights and drivers of business growth. By combining multiple data sources, the analysis tracks total revenue, customer traffic patterns, peak order hours, and menu item performance.

## Dataset Description
The analysis utilizes four interconnected datasets from the restaurant's operational database:
*   `orders.csv`: Contains the unique ID, date, and time for every customer order.
*   `order_details.csv`: Links specific items, quantities, and order IDs.
*   `pizzas.csv`: Details the size, type ID, and price for each available pizza variation.
*   `pizza_types.csv`: Stores the official name, category, and ingredient list for each pizza type.

## Technical Skills & Tools Used
*   **Language:** Python
*   **Data Manipulation:** Pandas
*   **Data Visualization:** Matplotlib, Seaborn
*   **Development Environment:** Jupyter Notebook
*   **Key Concepts:** Data cleaning, multi-table joining, datetime parsing, data aggregation, and data visualization.

## Key Insights
*   **Overall Performance:** Generated **$817,860.05** in total revenue from **49,574** pizzas sold across **21,350** unique orders.
*   **Menu Metrics:** The menu features **32** distinct types of pizzas with an average item price of **$16.44**.
*   **Peak Rush Hours:** Operational data reveals a double-peak rush pattern. The busiest times occur at lunch (**12:00 PM - 1:00 PM**) and dinner (**5:00 PM - 6:00 PM**).
*   **Weekly Trends:** **Friday** stands out as the most profitable operating day of the week ($136,073.90), while Sunday brings in the lowest revenue.
*   **Top Bestseller:** **The Classic Deluxe Pizza** is the most popular item with **2,453** units sold.
*   **Underperforming Items:** **The Brie Carre Pizza** significantly lags behind the rest of the menu, selling only **490** units throughout the entire year.

## How to Run the Project
1. Clone this repository to your local machine.
2. Ensure you have `pandas`, `matplotlib`, and `seaborn` libraries installed.
3. Place the four dataset CSV files in the same directory as the notebook.
4. Run the Jupyter Notebook cells sequentially to view the analysis and generated charts.
