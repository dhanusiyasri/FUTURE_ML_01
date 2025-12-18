#Task-1: 📊 AI-Powered Sales Forecasting Dashboard

## 📌 Project Overview
This project demonstrates an **end-to-end sales forecasting and business intelligence solution**.  
Historical sales data from the **Sample Superstore dataset** is used to forecast future sales using the **Prophet time-series forecasting model**, and the results are presented through an **interactive Power BI dashboard**.

The project combines:
- **Machine Learning (Time Series Forecasting)**
- **Data Modeling**
- **Business Intelligence Visualization**

---

## 🎯 Project Objectives
- Analyze historical sales trends
- Forecast future sales using a time-series model
- Understand seasonality patterns in sales
- Visualize actual vs forecasted sales
- Build an interactive and professional Power BI dashboard

---

## 🗂 Dataset
**Sample Dataset**

Key columns used:
- `Order Date` → Time dimension
- `Sales` → Target variable
- `Category`, `Region` → Optional business filters

The dataset contains **transaction-level data** with multiple orders per day.

---

## 🧠 Concepts Learned

### 1️⃣ Time Series Analysis
- Importance of date order
- Historical values influencing future predictions

### 2️⃣ Data Aggregation
- Aggregating transactional data into **daily sales**
- Preparing clean time-series data

### 3️⃣ Prophet Forecasting Model
- Trend detection
- Weekly and yearly seasonality
- Forecast uncertainty using confidence intervals

### 4️⃣ Forecast Horizon
- Predicting future values for a defined period (90 days)

### 5️⃣ Confidence Intervals
- Understanding upper and lower bounds
- Risk-aware forecasting

### 6️⃣ Power BI Data Modeling
- Difference between **columns and measures**
- Creating and using a **Date Table**
- Implementing **star schema**

### 7️⃣ DAX Measures
- Dynamic calculations using filter context
- Aggregations for visuals and KPIs

### 8️⃣ Interactive Dashboards
- Slicers and filters
- Context-aware visual updates

---

## 🔄 Project Workflow
- Raw Sales Data
- Data Cleaning
- Daily Sales Aggregation
- Time Series Forecasting (Prophet)
- Export Forecast Results
- Power BI Data Modeling
- Interactive Dashboard & Insights

---

## 🧪 Methodology & Steps

### Step 1: Data Cleaning
- Converted `Order Date` to date format
- Removed inconsistencies

### Step 2: Aggregation
- Grouped sales by date
- Calculated daily total sales

### Step 3: Forecasting Preparation
- Renamed columns (`ds`, `y`) as required by Prophet

### Step 4: Model Training
- Trained Prophet model with:
  - Weekly seasonality
  - Yearly seasonality

### Step 5: Forecast Generation
- Generated future dates (90 days)
- Predicted future sales values
- Extracted confidence intervals

### Step 6: Export Results
- Saved forecast output as CSV

### Step 7: Power BI Data Modeling
- Imported historical and forecast data
- Created a **Date Table**
- Built relationships using star schema

### Step 8: DAX Measures
- Actual Sales
- Forecast Sales
- Forecast Upper Bound
- Forecast Lower Bound

### Step 9: Dashboard Creation
- Line charts
- Area charts
- KPI cards
- Slicers

---

## 📈 Seasonality Analysis

### 🔹 Monthly Sales Seasonality
- Displays average sales by month
- Highlights repeating monthly patterns

### 🔹 Weekly Sales Seasonality
- Displays average sales by day of week
- Shows weekday vs weekend behavior

These visuals explicitly represent the **seasonality learned by the forecasting model**.

---

## 🎨 Dashboard Design & Formatting Enhancements

### Visual Alignment
- Enabled gridlines and snap-to-grid
- Used align and distribute tools
- Maintained consistent spacing

### Consistent Sizing
- Standardized width and height of visuals
- Created a clean grid-based layout

### KPI Styling
- Enhanced font size and contrast
- Added subtle backgrounds and borders

### Chart Formatting
- Reduced clutter
- Applied consistent color themes
- Differentiated actual vs forecasted sales clearly

---

## 📊 Power BI Dashboard Components

- **Line Chart**: Actual vs Forecast Sales
- **Area Chart**: Forecast Confidence Interval
- **Bar Charts**: Monthly & Weekly Seasonality
- **KPI Cards**: Total Actual & Forecast Sales
- **Slicers**: Year-based filtering

---

## 🛠 Tools & Technologies Used
- **Python**
  - pandas
  - Prophet
  - matplotlib
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **CSV** for data exchange

---

## 📌 Key Insights
- Sales exhibit clear **seasonal patterns**
- Forecasts provide actionable future trends
- Confidence intervals help assess uncertainty
- Interactive dashboard supports business decision-making

---

## 🚀 Use Cases
- Sales planning and demand forecasting
- Business performance monitoring
- Decision support systems
- Analytics portfolio project

---

## 📬 Acknowledgment
This project was completed as part of **Future Interns – Machine Learning Task 1**, focusing on practical implementation of forecasting and analytics concepts.

---

## 👤 Author
**Dhanusiya Sri M**  
Machine Learning & Data Analytics Enthusiast

