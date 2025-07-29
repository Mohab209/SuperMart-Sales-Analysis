# SuperMart-Sales-Analysis

**SuperMart Global Sales – End-to-End Data Cleaning & Analysis with Excel**

---

### 📌 Project Description:

This project simulates a real-world data analytics scenario where the dataset is **not clean**, mimicking the typical challenges faced in actual business environments.

Using Excel and Power Query, I cleaned, analyzed, and visualized a fictional global sales dataset to identify **loss patterns, customer behavior,** and **profit distribution** — then wrapped everything into a clean, interactive dashboard.

---

### 🎯 Objectives:

* Practice data cleaning on a semi-dirty dataset
* Perform exploratory analysis on sales, profits, and customer segments
* Build a clear, interactive dashboard for business insight
* Think like a real Data Analyst, not just a spreadsheet user

---

### 🛠 Tools Used:

| Tool         | Purpose                        |
| ------------ | ------------------------------ |
| Excel        | Main analysis & dashboard      |
| Power Query  | Data cleaning & transformation |
| Pivot Tables | Summarization & filtering      |
| Charts       | Data visualization             |

---

### 🧹 Step 1: Data Cleaning

**Challenges identified:**

* ❌ Invalid `Order Date` values (some in 2026)
* 🔁 Duplicate `Order ID`s
* 🕳️ Null values in `Customer Segment` and `Payment Method`
* 🔠 Inconsistent formatting in `Product Name`
* ⚠️ Illogical pricing: `Cost Per Unit > Unit Price`

**How I solved them:**

* Removed future-dated orders using conditional logic
* De-duplicated records in Power Query
* Removed rows with missing critical values (no assumptions made)
* Standardized product names using `Format` in Power Query
* Flagged unusual cost/price records for business review

---

### 📊 Step 2: Exploratory Data Analysis

Focused on identifying patterns related to **losses and performance**, such as:

* 🔍 Which countries and cities have the highest number of loss-generating orders?
* 👤 Which customer segments are contributing to losses?
* 🧾 Profit trends over time
* 🏷️ Sales and profit breakdown by product category

---

### 📈 Step 3: Dashboard Design

The final dashboard (built in Excel) includes:

* **Charts**:

  * Profit trend (Line chart)
  * Loss breakdown by country & segment (Bar charts)
  * Profit by product category (Pie & column)
  * Customer behavior analysis (Segment distribution)
* **Slicers**:

  * Country filter
  * Product category filter

---

### 📝 Key Insights:

* Some cities show repeated negative profit trends → possible pricing/operational issues
* Specific customer segments contribute more to loss orders
* Certain products have inconsistent profit margins
* Visual indicators helped isolate where deeper investigation is needed

---

### 🙌 Acknowledgment:

Special thanks to **Ahmed Abd Elbaky** for helping me learn Excel professionally and guiding my thought process like a real-world analyst.

---



### 🧑‍💻 About Me:

I'm a data analysis student passionate about building real, hands-on projects that simulate the challenges of actual business data.
This project reflects my growth in cleaning, thinking, and storytelling with data.

---
