# 📊 Sales Analytics Dashboard

An interactive and responsive **Sales Analytics Dashboard** built with **HTML, CSS, JavaScript, and Chart.js** to visualize sales performance, profitability, customers, products, categories, sales channels, and regional performance.

The dashboard provides a modern business-intelligence style interface with dynamic KPIs, interactive charts, advanced filters, data tables, automated insights, CSV export, print functionality, and light/dark themes.

---

## 🚀 Project Overview

The **Sales Analytics Dashboard** is designed to transform sales transaction data into meaningful business insights through an intuitive web-based interface.

It enables users to:

* Monitor overall sales and profitability
* Analyze sales and profit trends
* Compare customer segments
* Evaluate category performance
* Analyze regional and state-level sales
* Identify top-performing products and customers
* Review salesperson performance
* Generate dynamic business insights
* Search, sort, paginate, and export sales records

## The current project uses a **locally generated synthetic dataset of 850 sales transactions** for demonstration purposes.

## ✨ Key Features

### 📌 KPI Overview

The dashboard dynamically calculates and displays:

* 💰 Total Sales
* 📈 Total Profit
* 🧾 Total Orders
* 👥 Total Customers
* 🛒 Average Order Value
* 📊 Profit Margin

These KPIs automatically update according to the selected filters.

---

### 🔎 Interactive Filters

Users can filter the dashboard by:

* Date Range
* Year
* Month
* Region
* State
* City
* Category
* Product
* Customer Segment
* Sales Channel

Filters can be applied or reset, allowing users to explore specific portions of the sales dataset.

---

## 📈 Data Visualizations

The dashboard contains multiple interactive visualizations powered by **Chart.js**.

### Sales & Profit Trend

Analyze sales and profit trends using:

* Daily
* Monthly
* Quarterly
* Yearly

granularity.

### Customer Segment

Visualizes sales distribution across different customer segments.

### Sales vs Profit

Provides a comparative view of sales and profit performance.

### Category Performance

Analyzes sales performance across product categories.

### Regional Sales

Analyze performance:

* By Region
* By State

### Top 10 Products

Highlights the top products based on sales performance.

---

## 🌍 Regional Performance

The dashboard provides an interactive regional analysis section.

Users can select a region to view detailed metrics including:

* Sales
* Profit
* Orders

This allows businesses to identify regional performance patterns and opportunities.

---

## 🏆 Top Performers

The dashboard automatically identifies top-performing entities from the filtered dataset:

* Top 5 Products
* Top 5 Customers
* Top 5 Regions
* Top Salespersons

The ranking logic dynamically recalculates based on the active filters.

---

## 💡 Dynamic Business Insights

The built-in insights engine automatically analyzes filtered data and generates observations such as:

* Highest-revenue category
* Leading region
* Top-performing product
* Top customer
* Best-performing month
* Lowest-margin category
* Period-over-period performance changes

This makes the dashboard more than just a visualization tool—it provides an analytical layer for interpreting sales data.

---

## 📋 Sales Performance Table

The detailed sales table provides transaction-level information including:

| Field    | Description              |
| -------- | ------------------------ |
| Order ID | Unique order identifier  |
| Date     | Order date               |
| Customer | Customer name            |
| Product  | Product name             |
| Category | Product category         |
| Region   | Sales region             |
| State    | Customer/order state     |
| Sales    | Sales value              |
| Quantity | Units sold               |
| Profit   | Profit generated         |
| Margin   | Profit margin percentage |

The table supports **search, column sorting, pagination, CSV export, and printing**.

---

## 📥 Data Export

Users can export the currently displayed/filtered sales records as a **CSV file** directly from the browser.

The exported dataset includes order, customer, product, category, geographical, sales, quantity, profit, and margin information.

---

## 🌓 Dark & Light Mode

The dashboard supports both:

* ☀️ Light Mode
* 🌙 Dark Mode

The selected theme is stored locally so the preference can persist between sessions.

---

## 📱 Responsive Design

The dashboard is designed to work across:

* 💻 Desktop
* 🖥️ Laptop
* 📱 Tablet
* 📲 Mobile

The sidebar, charts, filters, KPI cards, and data tables adapt to smaller screen sizes.

---

## 🎨 UI & Design

The dashboard follows a professional business analytics design system featuring:

* Modern card-based layout
* Deep navy and gold visual theme
* Responsive grid system
* KPI cards
* Interactive charts
* Clean data tables
* Sticky navigation
* Light/dark themes
* Responsive sidebar
* Accessible visual hierarchy

---

## 🛠️ Technologies Used

| Technology               | Purpose                               |
| ------------------------ | ------------------------------------- |
| **HTML5**                | Dashboard structure                   |
| **CSS3**                 | Styling, responsive layout and themes |
| **JavaScript**           | Data processing and interactivity     |
| **Chart.js**             | Interactive data visualizations       |
| **Font Awesome**         | Dashboard icons                       |
| **Google Fonts**         | Manrope & Inter typography            |
| **Browser LocalStorage** | Theme preference                      |

## The project loads Chart.js and supporting visual resources directly in the HTML file.

## 📂 Project Structure

```text
sales-dashboard/
│
├── sales-dashboard.html
└── README.md
```

The current implementation is packaged as a **single HTML file** containing the dashboard structure, CSS, sample data generation, and JavaScript functionality.

---

## 📊 Dataset

The dashboard currently uses **synthetically generated Indian retail/B2B sales data**.

The generated records contain fields such as:

```text
Order ID
Order Date
Customer ID
Customer Name
Customer Segment
Product ID
Product Name
Category
Sub Category
Region
State
City
Salesperson
Sales Channel
Quantity
Sales
Discount
Cost
Profit
Profit Margin
```

The dataset generator uses a deterministic random process so the demonstration data remains stable across reloads.

---

## ▶️ How to Run

### Option 1 — Open Directly

1. Download or clone the repository.
2. Open `sales-dashboard.html`.
3. The dashboard will run directly in your browser.

### Option 2 — VS Code

Open the project in **Visual Studio Code** and use a local development server such as **Live Server**.

```bash
git clone YOUR_REPOSITORY_URL
cd sales-dashboard
```

Then open:

```text
sales-dashboard.html
```

---

## 🔄 Connecting Your Own Dataset

The current dashboard uses a local `generateSalesData()` function to create demonstration records.

For a real-world project, this function can be replaced with data loaded from:

* CSV
* JSON
* REST API
* Database backend
* Excel-converted data
* Cloud data source

This makes the dashboard suitable as a foundation for a real sales analytics application.

---

## 🎯 Business Use Cases

This dashboard can support:

* Sales performance monitoring
* Revenue analysis
* Profitability analysis
* Regional sales analysis
* Product performance analysis
* Customer analysis
* Salesperson performance tracking
* Category-level analysis
* Sales channel comparison
* Management reporting
* Business decision support

---

## 🔮 Future Enhancements

Possible future improvements include:

* [ ] Connect live database/API
* [ ] Upload CSV/Excel files directly
* [ ] User authentication
* [ ] Real-time data updates
* [ ] Advanced date-range picker
* [ ] Forecasting and predictive analytics
* [ ] Customer retention analysis
* [ ] Automated PDF reports
* [ ] Cloud deployment
* [ ] Backend API integration
* [ ] Role-based dashboards

---

## 👨‍💻 Author

**Aditya Yadav**

**Aspiring Data Analyst | Excel | SQL | Power BI | Python | Data Visualization**

This project was developed as part of a practical **Data Analytics portfolio** to demonstrate dashboard development, data analysis, visualization, and business intelligence skills.

---

## ⭐ Project Highlights

> **Interactive • Responsive • Data-Driven • Business-Focused**

A complete front-end sales analytics solution designed to convert raw transaction data into clear, actionable business insights.

---

## 📄 License

This project is intended for **educational, portfolio, and demonstration purposes**.

---

### ⭐ If you found this project useful, consider giving the repository a star!
