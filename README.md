---

# AC Price Analysis using Web Scraping (Flipkart Data)

## Project Overview

This project performs **web scraping on Flipkart** to collect data on **Air Conditioner (AC) prices, brands, features, and specifications**, followed by **data cleaning, analysis, and visualization** to gain market insights.
It demonstrates how data can be automatically extracted from e-commerce sites and analyzed to understand **pricing trends and performance across brands**.

---

## Objectives

* Extract AC product data (name, price, capacity, ratings, etc.) from Flipkart using Python.
* Clean and structure the collected data for analysis.
* Analyze pricing trends and performance metrics of ACs.
* Visualize insights using graphs and charts.

---

## Technologies Used

* **Python**
* **Libraries:**

  * `requests` – for fetching webpage data
  * `BeautifulSoup` – for parsing HTML content
  * `pandas` – for data manipulation and cleaning
  * `matplotlib` / `plotly` – for visualization
  * `numpy` – for numerical computations

---

##  Key Steps

1. **Web Scraping:**
   Extracted AC details (Brand, Model, Capacity, Star Rating, Inverter type, Power Consumption, Price, etc.) from Flipkart pages.

2. **Data Cleaning & Processing:**

   * Removed missing or inconsistent entries
   * Converted data types (e.g., price to numeric)
   * Organized columns for analysis

3. **Data Analysis & Visualization:**

   * Average price by brand and capacity
   * Energy efficiency vs. price insights
   * Visualization of brand-wise price distribution

4. **Insights:**

   * Identified the most affordable and premium AC brands
   * Compared inverter vs. non-inverter models
   * Highlighted price-performance relationships

---

## Project Structure

```
AC-Price-Analysis-Using-WebScrapping/
│
├── AC Price Analysis Using WebScrapping.ipynb   # Main project notebook
├── data/                                        # (Optional) scraped data files
├── images/                                      # (Optional) charts or plots
└── README.md                                    # Project documentation
```

---

##  How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/AC-Price-Analysis-Using-WebScrapping.git
   cd AC-Price-Analysis-Using-WebScrapping
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:

   ```bash
   jupyter notebook "AC Price Analysis Using WebScrapping.ipynb"
   ```

---

##  Future Enhancements

* Automate scraping with pagination and scheduling.
* Add interactive dashboards using **Streamlit** or **Power BI**.
* Compare data across multiple e-commerce platforms (Amazon, Croma, etc.).

---

##  Author

**Surya Namburi**
https://www.linkedin.com/in/suryaprakashnamburi/
Passionate about Data Analytics | Web Scraping | Python Automation

---
