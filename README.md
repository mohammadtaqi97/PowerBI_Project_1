# 📊 Superstore Sales Dashboard | Power BI Project

An interactive **Power BI dashboard** that analyses the **Sample – Superstore** retail dataset to track sales, profit, quantity sold and discounts across product categories, regions and shipping modes.

> **Project 1** of my **Data Science and AI/ML** course at **Red & White Multimedia Education, Bhavnagar**.

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Objectives](#-objectives)
3. [Dataset](#-dataset)
4. [Dashboard Structure](#-dashboard-structure)
5. [Key Metrics (KPIs)](#-key-metrics-kpis)
6. [Visualizations](#-visualizations)
7. [Interactivity](#-interactivity)
8. [Key Insights](#-key-insights)
9. [Tools & Skills](#-tools--skills-used)
10. [How to Open This Project](#-how-to-open-this-project)
11. [Screenshots](#-screenshots)
12. [Future Improvements](#-future-improvements)
13. [Author](#-author)

---

## 🔎 Project Overview

Businesses generate huge amounts of sales data, but raw tables make it hard to see what is working and what is not. This project turns the Superstore sales data into a clean, interactive dashboard so a manager can answer questions like:

- How much total **revenue** and **profit** are we generating?
- Which **product category** sells the most?
- Which **region** is the most (or least) profitable?
- How do **discounts** relate to profit?
- Which **shipping modes** are used most?

It is my first end-to-end Power BI project, covering data loading, modelling, visual design and interactivity.

## 🎯 Objectives

- Load and explore a real-world retail dataset in Power BI.
- Build **KPI cards** for the most important business numbers.
- Compare performance across **Category** and **Region** using bar charts.
- Add **slicers** so users can filter the whole report instantly.
- Provide a separate **data table page** for detailed record-level inspection.

## 🗂️ Dataset

| Item | Details |
|------|---------|
| **Name** | Sample – Superstore |
| **Type** | Retail / e-commerce sales transactions |
| **Format** | Imported into Power BI as a single table |

**Columns used in this report:**

| Column | Description |
|--------|-------------|
| `Customer-ID` | Unique customer identifier |
| `Product Name` | Name of the product sold |
| `Category` | Product category |
| `City` | City of the order |
| `Segment` | Customer segment |
| `Region` | Sales region |
| `Ship Mode` | Shipping method used |
| `Sales` | Revenue generated |
| `Quantity` | Units sold |
| `Discount` | Discount applied |
| `Profit` | Profit earned |

## 🧭 Dashboard Structure

The report has **2 pages**:

### Page 1: Observation, Visualisation, Slicers (1920 × 1080)
The main analytical dashboard with KPI cards, charts and filters.

### Page 2: Data Table (1280 × 720)
A full-page table showing record-level details: Customer ID, Product Name, Category, City, Segment, Sales, Discount, Profit and Ship Mode.

## 📈 Key Metrics (KPIs)

Four KPI cards sit across the top of the dashboard:

| KPI Card | Calculation |
|----------|-------------|
| 💰 **Total Sales** | Sum of `Sales` |
| 📦 **Total Quantity** | Sum of `Quantity` |
| 📊 **Total Profit** | Sum of `Profit` |
| 🏷️ **Average Discount in Percentage** | Average of `Discount` |

## 📊 Visualizations

| Visual | Type | What it shows |
|--------|------|---------------|
| **Total Sales** | Bar chart | Sales by product **Category** (red bars, sorted high to low) |
| **Total Profit** | Clustered bar chart | Profit by **Region** (grey bars with data labels) |
| **Ship Mode table** | Table | Shipping modes, filtered to *Standard Class* and *Second Class* |
| **KPI Cards** | Card visuals | Total Sales, Total Quantity, Total Profit, Average Discount |
| **Data Table** | Table (page 2) | Detailed transaction-level records |

Design choices: bold titles, large readable fonts (15–30 pt), data labels placed outside bars, and a dark theme with contrasting red and grey series colors.

## 🎛️ Interactivity

- **Category slicer**: filter the entire page by product category.
- **Region slicer**: filter the entire page by region.
- Slicers are **synced** (sync groups), so the selection stays consistent across the report.
- **Cross-filtering**: clicking a bar in one chart updates the other visuals.

## 💡 Key Insights

> ✏️ *Fill in these points with the actual numbers from your dashboard before publishing.*

- **Top category by sales:** `[Category name]` generated the highest sales with `[value]`.
- **Most profitable region:** `[Region]` leads in profit, while `[Region]` is lowest.
- **Discount impact:** The average discount is `[x]%`; compare it with profit to see whether heavy discounting hurts margins.
- **Shipping:** `[Standard Class / Second Class]` is the most common shipping mode.
- **Overall:** Total sales of `[value]` produced a profit of `[value]` on `[quantity]` units.

## 🛠️ Tools & Skills Used

- **Power BI Desktop**: report design and publishing
- **Data modelling**: importing and structuring the Superstore table
- **Aggregations**: Sum, Average
- **Visual design**: KPI cards, bar charts, tables, formatting and themes
- **Filtering**: slicers, sync groups, visual-level filters
- **Data storytelling**: turning raw data into business insights

## 🚀 How to Open This Project

1. Install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free, Windows).
2. Download or clone this repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
3. Open `Project1_PowerBI.pbix` in Power BI Desktop.
4. Use the **Category** and **Region** slicers to explore the data, and switch to the **Data Table** page for detailed records.

## 🖼️ Screenshots

> Add your screenshots to a folder named `screenshots/` and update the paths below.

| Dashboard | Data Table |
|-----------|------------|
|<img width="1211" height="690" alt="Screenshot 2026-10-30 140850" src="https://github.com/user-attachments/assets/bf1481df-e1b1-4a53-b2bb-4a494b7f356d" />
| <img width="1143" height="648" alt="Screenshot 2026-10-30 141034" src="https://github.com/user-attachments/assets/cb373d79-fe4d-45ea-a58e-6d49eb5314b3" />
 |

## 🔮 Future Improvements

- Add a **date/time** analysis (monthly and yearly sales trend line).
- Add a **geographic map** of sales by state or city.
- Create **DAX measures** such as Profit Margin %, Year-over-Year growth.
- Add **Segment** and **Sub-Category** breakdowns.
- Publish to **Power BI Service** and share as a live dashboard.
- Extend the project with **Python / ML** (sales forecasting, customer segmentation) as part of my AI/ML learning.

## 👤 Author

**Mohammad Taqi Panjwani**
🎓 Student, Data Science and AI/ML Course
🏫 Red & White Multimedia Education, Bhavnagar, Gujarat

⭐ If you found this project useful, consider giving the repository a star!

*Created as part of my Data Science and AI/ML coursework, Red & White Multimedia Education, Bhavnagar.*
