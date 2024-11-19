# Station_Vitamine

# Station Vitamine Data Analysis Project

## 📋 Introduction
This project focuses on analyzing sales, waste, and vendor data for Station Vitamine, a juice store. The goal is to improve inventory management, reduce waste, and evaluate vendor performance to optimize operations. The project uses Python to process data, generate insights, and create visualizations.

### Objectives:
- Achieve a **15% reduction in excess inventory** by analyzing daily sales data and adjusting stock levels.
- Minimize juice waste by **20%**, as measured by weekly reports, by recommending loss reduction strategies.
- Evaluate vendor performance based on quality, cost, and delivery time for ingredient procurement.
- Identify top-selling products and busiest operational hours.


---

## 🛠️ Technologies
The following technologies and libraries were used in this project:

- **Programming Language:** Python
- **Libraries:**
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Other: `openpyxl`
- **Tools:** Jupyter Notebook

---

## ✨ Features

### Comprehensive Data Analysis:
- Analysis of sales trends and waste patterns over a 3-month period.
- Vendor performance evaluation based on cost, quality, and delivery reliability.

### Dynamic Visualizations:
- Side-by-side comparisons of vendors using bar plots and line charts.
- Waste and sales trends plotted for easier interpretation.

### Actionable Insights:
- Inventory recommendations to balance supply and demand.
- Identification of busiest hours and product performance for better staffing and stocking.

---

## 🖥️ Installation

### Prerequisites:
- Python (3.8 or later)


# 📊 Usage

### Instructions:
1. **Load the Dataset**:  
   The dataset includes sales, waste, and vendor performance data for the analysis.

2. **Run the Analysis**:  
   Use the Jupyter Notebook file (`Vitamin_Station.ipynb`) to preprocess data and generate visualizations.

3. **Visualize Insights**:  
   Check plots such as:
   - **Sales vs. Waste by Product**
   - **Total Waste Trends (3-Month Period)**
   - **Vendor Score Comparisons**

4. **Interpret Results**:  
   Use the insights to implement operational improvements.

---


### 📈 Sample Visualizations:
- **Vendor Score Comparison**
- **Sales vs. Waste by Product**
- **Weekly Waste Trends by Product**

---

# Comprehensive Project Conclusion for Station Vitamine

## Objective 1: Reduce Excess Inventory and Improve Stock Management

### Key Findings:
- **Sales vs. Waste by Product**: Products like *Super Cup*, *Vitamin C*, and *Vita Pro* consistently sell well, showing high demand and lower relative waste.
- Products like *Peanut Cacao Smoothie* and *Smoothie Très Baies* have higher waste proportions compared to sales, suggesting overproduction or low demand.

### Recommendations:
1. Maintain stock levels of at least **20 units per day** for top-selling products like *Vitamin C* and *Super Cup* to meet consistent demand.
2. Reduce daily stock levels for slower-moving products, such as *Peanut Cacao Smoothie*, to align production with demand trends and minimize waste.
3. Implement **demand forecasting** using historical trends to dynamically adjust inventory.

---

## Objective 2: Minimize Juice Waste

### Key Findings:
- **Total Weekly Waste (All Products)**: Waste trends stabilize mid-week and decrease towards the weekend, indicating inefficiencies in weekday production planning.
- **Weekly Waste Trends by Product**: Consistent waste levels were noted for items like *Smoothie Mango* and *Energy Plus+*.

### Recommendations:
1. Optimize production schedules by creating **smaller batches mid-week** and increasing production for peak days like Friday and Saturday.
2. Introduce **promotional offers** or discounts for slow-moving products nearing expiration to reduce waste.
3. Regularly analyze waste trends and **adjust production plans weekly**.

---

## Objective 3: Evaluate Vendor Performance

### Key Findings:
- **Comparison of Vendor Scores Across Criteria**: *Vendor 3* emerged as the best option, excelling in cost, delivery time, and quality.
- **Comparison of Vendor Scores Across Products**: *Vendor 3* consistently scored highly across multiple products.

### Recommendations:
1. Select *Vendor 3* as the **primary supplier** for most ingredients due to lower delivery costs and reliable quality.
2. Use *Vendor 2* selectively for **premium products** requiring higher quality standards.
3. Establish **regular reviews** with vendors to maintain consistent service and proactively address issues.

---

## Objective 4: Identify Top-Selling Products and Busiest Operational Hours

### Key Findings:
- **Total Orders by Product Name**: *Vitamin C*, *Vita Pro*, and *Super Cup* are the top-selling products, consistently outperforming others.
- Analysis of purchase timings indicates **peak operational hours** during lunchtime (11 AM–2 PM).

### Recommendations:
1. Ensure **higher stock levels** for top-performing products during peak hours.
2. Strategically staff and promote during **lunch hours** to maximize sales.
3. Consider **bundling top-selling products** with slower-moving ones to increase overall sales.

---

## Overall Business Impact

This analysis provides actionable insights to:
- Optimize inventory management by aligning stock levels with demand trends.
- Minimize waste through targeted production and promotional strategies.
- Leverage vendor performance evaluations to streamline procurement processes.
- Focus operational resources on high-demand products and peak hours to improve profitability.

### Future Steps:
1. Automate inventory tracking with **real-time dashboards**.
2. Develop **predictive models** for sales and waste trends to improve planning accuracy.
3. Collect and integrate **customer feedback data** to refine product offerings and pricing strategies.


### 📝 Notes:
- This project can be further expanded to include **predictive models for inventory optimization**.
- Future work may involve **automation of insights generation and reporting**.

- Jupyter Notebook
- Required Python packages:
  ```bash
  pip install pandas numpy matplotlib seaborn plotly openpyxl

