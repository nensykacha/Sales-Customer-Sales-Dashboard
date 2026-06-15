# 📊 Advanced Sales & Customer Intelligence Dashboard (End-to-End Power BI Project)

## 📝 Project Overview
This project is an enterprise-grade Power BI dashboard designed to analyze sales performance, customer behavior, and return trends. Built on a clean Star Schema, it leverages advanced DAX calculations, interactive UX elements, Row-Level Security (RLS), and mobile optimization to deliver deep business insights.

---

## 🛠️ Key Features Implemented

### 1️⃣ Data Modeling & Architecture
* **Star Schema Layout:** Developed a clean data model establishing robust relationships between Fact and Dimension tables using Primary and Foreign keys.
* **Optimized Report View:** Hid unnecessary fields, system keys, and technical columns from the report view to provide a clean workspace for end-users.
* **Consistent Conventions:** Followed industry-standard naming conventions across all tables, columns, and measures.

### 2️⃣ Advanced DAX Measures & Analytics
* **Dynamic Analytics:** Developed key measures using `CALCULATE`, `FILTER`, `ALL`, `SUMX`, `COUNTX`, and `AVERAGEX` for complex aggregations.
* **Data Integration:** Utilized `RELATED` to seamlessly fetch dimension attributes into calculation contexts.
* **KPI Classification:** Implemented logical `SWITCH` operations for automated KPI classification.
* **Calculated Columns:** Created customized columns for customer full names (First + Last), optimized Year-Month sorting formats, and dynamic profit margin classification.

### 3️⃣ Time Intelligence & Trend Analysis
* **Growth Metrics:** Implemented advanced time-intelligence logic to calculate **YoY (Year-over-Year)**, **MoM (Month-over-Month)**, and **YTD (Year-to-Date)** performance for both Sales and Returns.
* **Trend Identification:** Uncovered seasonal purchase patterns and return behavior over specific timelines.

### 4️⃣ Dashboard Layout & Visualizations
Structured into **1 Main Summary Page, 2 Detail Pages, and 1 dedicated Drillthrough Page**:
* **Executive Summary:** Deployed Cards, KPI Cards, and Donut Charts for quick executive-level insights.
* **Advanced Visuals:** Integrated Line and Bar Charts equipped with trend lines and automated forecasts for forward-looking sales data.
* **Deep-Dive Analytics:** Configured structured Matrix visuals with custom conditional formatting.
* **Top N Analytics:** Implemented dynamic filters to showcase the *Top N Products by Sales* and *Top N Customers by Profit*.

### 5️⃣ Filtering, Interaction & UX Enhancement
* **Multi-Aspect Slicers:** Included responsive slicers for Product, Customer Segment, Region, and Date.
* **Advanced Interactivity:** Enabled cross-filtering, Drill Up/Down capabilities, and dynamic Page Drillthroughs.
* **Collapsible Slicer Panel:** Engineered a sleek, space-saving collapsible slicer panel using Bookmarks and Selection panes to maximize screen real estate.
* **Custom Navigation:** Integrated custom navigation buttons and bookmarks for intuitive page-switching.
* **Numeric Range Parameter:** Implemented custom numeric range filtering (`GENERATESERIES` from 0 to 12,000) for bespoke pricing/sales interval testing.
* **One-Click Reset Button:** Created a custom button using bookmarks to instantly clear all filters and restore the original dashboard view.
* **Interactive Tooltips:** Engineered customized tooltips containing mini visual summaries that display on hover.

### 6️⃣ Mobile-Optimized Layout
* **On-The-Go Insights:** Specifically designed and optimized key layout sheets for mobile devices.
* **Mobile Prioritization:** Structured the viewport to prioritize high-level KPI cards and vital Top N visuals for quick reading on phones.

### 7️⃣ Enterprise Security (RLS)
* **Row-Level Security:** Created secure data access roles for Region Managers.
* **Access Control:** Restricted visibility so regional leads can only view data corresponding to their assigned territory.
* **Validation:** Extensively tested and verified RLS rules utilizing the "View As" functionality in Power BI Desktop.

---

## 📸 Dashboard Previews

### 1️⃣ Main Dashboard View
This is the central executive summary showcasing high-level KPIs like Total Revenue ($844K), Total Orders, and overall Return Rate, alongside regional distribution and trend forecasting.

<img width="593" height="335" alt="Main" src="https://github.com/user-attachments/assets/bafa92b5-319a-40f5-94b1-03d6cc40dd4c" />


### 2️⃣ Advanced Interactive Tooltips (Deep-Dive Analysis)
Hovering over customer profiles automatically triggers an analytical tooltip overlay. This feature displays granular data such as sub-category sales and total amounts dynamically, providing instant insights without cluttering the canvas.

<img width="589" height="332" alt="Returns" src="https://github.com/user-attachments/assets/df04067e-d42f-4206-b93e-851c35a871ea" />

### 3️⃣ Sales Details & Matrix View
A structured matrix sheet incorporating advanced conditional formatting for profit margins, YoY sales growth tracks, and performance categorization based on distinct enterprise metrics.

<img width="591" height="335" alt="Sales" src="https://github.com/user-attachments/assets/e509da00-7a9c-44bd-b956-3cbf495ef2ac" />


### 4️⃣ Mobile-Optimized Layout
Engineered for on-the-go analytics, the mobile layout restructures visual priority, stacking critical KPI cards and operational revenue statistics seamlessly for handheld screen resolutions.

<img width="338" height="338" alt="Mobile" src="https://github.com/user-attachments/assets/d40fb0ab-9038-483e-9dd8-53a2c81e5599" />

---

---

## 📂 Repository Structure & How to Run
* `Sales-Customer-Sales-Dashboard.pbix` - The core Power BI project file containing the data model, clean DAX measures, and interactive desktop layouts.
* `README.md` - Complete project documentation with previews.
