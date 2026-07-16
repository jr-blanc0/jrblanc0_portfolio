# jr-blanc0_portfolio
Analytics Portfolio

# Hi, I'm Jhon Robin A. Blanco 👋
### Aeronautical Engineer | Data Analyst

Welcome to my portfolio! I’m an **Aeronautical Engineering Graduate** who loves diving into data to find the stories behind the numbers. My engineering background taught me how to break down complex systems, build multi-variable models, and track down root causes—skills that map perfectly onto solving tough, data-driven business problems. 

I enjoy transforming messy, raw datasets into clean databases and building interactive, clear dashboards that help people make smarter decisions. Currently, I'm focused on mastering SQL, Excel, Tableau, Power BI, and Python to drive real-world business value. Take a look around my repositories to see some of my work, and feel free to connect!

---

## 🛠️ Technical Skills
* **Data Visualization & Analytics:** Tableau Public, MS Excel (Pivot Tables, Power Query)
* **Databases & Querying:** SQL (MySQL)
* **Engineering Tools:** AutoCAD, Autodesk Inventor

---

## 📊 Featured Personal Projects

### 1. AirBnB Market Performance Dashboard 
**Tools Used:** Tableau, MS Excel  
▶️ **[View Interactive Dashboard on Tableau Public](https://public.tableau.com/views/AirBnBFullproject_17837979180310/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)** | 📁 **[Repository Link](https://github.com/jr-blanc0/jrblanc0_portfolio/tree/c926bd54a89ef9bf5a420cf68df5661c1a552879/AirBnB%20Full%20Project)**

#### 📖 Overview
This project delivers an interactive Tableau dashboard designed to analyze local AirBnB market dynamics, providing property investors and hosts with data-driven insights to optimize pricing strategies and maximize ROI. By visualizing the relationships between property size, geographical location, seasonal demand, and overall market volume, this dashboard transforms raw rental data into actionable business intelligence. This project demonstrates my ability to clean complex datasets, design intuitive user experiences (UX/UI), and extract clear, strategic value from raw data.

* 📊**Data & Methodology:**
  * **Data Source**: Seattle AirBnB open dataset from Kaggle containing core relational tables mapping property listings, calendar scheduling metrics, and historical user reviews.
  * **Data Modeling & Joins**: Imported the multi-table Excel workbook structure into Tableau Desktop. Connected the primary listings table (3,600+ physical property rows) to the time-series calendar availability table via an Inner Join, explicitly overriding automated fields to map the relational listing_id to the base table id to enforce relational integrity.
  * **Visualization Stack**: Tableau Public / Desktop. Designed a multi-view dashboard using automatic layout sizing. The pipeline combines continuous time-series trend lines for full-year macro revenue tracking, coordinate spatial maps using underlying zip code boundaries accompanied by labels, and ranked bar charts evaluating capacity against average pricing thresholds.
* 💡**Key Findings:**
  * **Premium Pricing for Scale**: There is a clear linear, upward trend in rental pricing relative to property capacity. While 1-bedroom units average a baseline of **$96.20**, 6-bedroom listings command a premium average of **$584.80**, indicating that larger, group-oriented properties yield significantly higher margins per booking.
  * **High-Volume vs. High-Value Geographic Zones**: The listing market is heavily dominated by 1-bedroom units (1,811 total listings), yet geographical location dictates premium pricing far more than sheer volume. Zip codes such as **98134** and **98119** emerge as high-value corridors, generating the highest average pricing metrics despite not having the highest concentration of total listings.
  * **Strong Mid-Year Seasonal Revenue Scaling**: Seasonal demand builds aggressively through the first half of the year. Market revenue climbs rapidly from under **$1,000K** in late January, stabilizing into a sustained peak period between May and September at over **$2,000K**, providing hosts a clear window for optimized surge pricing during summer months.

<img src=git_images/airbnbproject.png>

---

### 2. Consumer Demographics & Bike Sales Dashboard
**Tools Used:** MS Excel (Advanced Formulas, Pivot Tables, Slicers)  
📁 **[Repository Link](https://github.com/jr-blanc0/jrblanc0_portfolio/tree/d18c98fddc0e2ceae7e01a58380de44696ed9ba9/Excel%20Project)**

#### 📖 Overview
This project features a comprehensive Excel-based data analytics pipeline and interactive dashboard designed to analyze customer demographics and isolate the key socioeconomic drivers behind bicycle purchases. Utilizing a dataset of 1,000 customers, the goal of this analysis is to help a retail marketing team optimize target campaigns by identifying high-conversion buyer personas. This portfolio piece demonstrates core competencies in data cleaning (standardizing unstructured values, treating duplicates), structural data modeling using nested logical conditions, pivot table aggregation, and executive-level dashboard design using interactive slicers.

* 📊**Data & Methodology:**
  * **Data Source**: A dataset containing 1,026 rows mapping structural customer records across 13 demographic and lifestyle variables (e.g., income, children, education, geography, and commute distances).
  * **Data Cleaning & Standardization**:
     * Executed Excel’s built-in **Remove Duplicates** functionality to strip out identical data rows, pruning the dataset down to 1,000 unique records.
     * Performed standardizing **Find and Replace** **(Ctrl + H)** macros to expand short-hand abbreviations into user-friendly classifications (**M** to **Married**, **S** to **Single**, **M** to **Male**, and **F** to **Female**).
     * Created a custom feature **"Age Brackets"** using nested **IF** logic to classify customers into clean marketing segments: **Adolescent** (under 31), **Middle Age** (31–54), and **Old** (55+).
     * Leveraged **Pivot Tables** for multi-dimensional aggregations, **Pivot Charts** for structural distribution, and interactive **Slicers** (Region, Education, and Marital Status) for dynamic dashboard cross-filtering.
* 💡**Key Findings:**
  * ✅Consumers with a commute distance of **0–1 miles** exhibit the highest conversion rates for bike purchases across almost all regions, identifying proximity as a primary purchasing trigger.
  * ✅The maximum average income of Males is $60,124. So, they purchased bikes more as compared to females who got 7% less average income than males.
  * ✅People in the Middle Age group (31-54 years) purchased 4 times more bikes as compared to the Adolescent and Old age groups.
<img src=git_images/excelproject.png>

---

## 🎓 Education & Certifications
* **B.S. in Aeronautical Engineering** - WCC Aeronautical & Technological College | July 2025
* **Introduction to Data Analysis** - Approved by IBM | July 2026
* **Google AI Professional** - Approved by Google | June 2026
* **AI for Data Analysis** - Approved by Google | June 2026
* **Safety Officer 2 (SO2)** - Approved by DOLE BOSH Certification | February 2026

---

## 📩 About Me
* **LinkedIn:** Jhon Robin Blanco (https://www.linkedin.com/in/jr-blanc0)
* **Email:** jhonrobinblanco@gmail.com
* **Tableau Public:** [jr_blanc0](https://public.tableau.com/app/profile/jhon.robin.blanco/vizzes)

If you found this project useful, give it a ⭐on GitHub
