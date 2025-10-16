# 🇮🇳 India General Election Results Analysis – 2024 (Power BI)

> Ever wondered how data reveals the real story behind the world’s largest democracy?

## Project Overview
This Power BI project provides a comprehensive analysis of the **India General Election 2024** results.  
It visualizes the performance of alliances and parties across states, regions, and constituencies using interactive dashboards.  
The project highlights key metrics, state-wise trends, constituency-level details, and drill-through capabilities for deeper insights.

---

## Dataset and Data Preparation
- **Dataset Source:** Kaggle (India General Election 2024 results)  
- **Steps performed in Power BI Desktop:**
  1. **Loaded CSV files** from the `Data/` folder into Power BI  
  2. **Data cleaning using Power Query Editor:**  
     - Checked column data types and quality  
     - Removed duplicates and unnecessary columns  
  3. **Data Modeling:**  
     - Created relationships between multiple tables to connect data properly  
  4. **KPI Metrics:**  
     - Total seats by NDA, I.N.D.I.A., and Others  
     - Seat share percentages  
     - State-wise total seats, party-wise seats, winning alliances  

---

## Dashboard Overview (6 Sheets)

### 1️⃣ Landing Page
- Provides an overview and **navigation to all major sheets** in the dashboard.  

### 2️⃣ Alliance Overview
- Displays **NDA, I.N.D.I.A., and Other parties’ seat counts**.  
- Includes **party logos** for visual clarity.  

### 3️⃣ State-wise Insights
- Shows **total seats, NDA seats, I.N.D.I.A. seats, and winning alliance** for each state.  
- Includes **drill-through feature** to explore state or constituency-level data.  

### 4️⃣ State Analysis with Slicer
- Interactive slicer on **state** to dynamically view:  
  - NDA, I.N.D.I.A., and Other alliance seat counts  
  - Party dominating the state  
  - Party-wise seat percentages  

### 5️⃣ Constituency Analysis
- Slicer on **constituency** to explore:  
  - Total votes, EVM votes, postal votes  
  - Total candidates  
  - Winner, runner-up, and second runner-up details  

### 6️⃣ Details Grid (Drill-through Page)
- Provides **granular constituency-level details:**  
  - Constituency name  
  - EVM votes, postal votes, total votes  
  - Winning candidate, runner-up, party, alliance, margin  
- Used as a **drill-through page** for all visuals in the dashboard  

---

## 📊 Key Numbers
- NDA: **292 seats (54%)**  
- I.N.D.I.A.: **234 seats (43%)**  
- Others: **17 seats (3%)**  

> ⚠️ Dataset reflects a post-election snapshot. NDA later officially updated to 293 seats.  

---

## Dashboard Snapshots
### Overview
![Overview Dashboard](Images/overview.png)

### State Landscape
![State Landscape](Images/state-landscape.png)

### Regional Insights
![Regional Insights](Images/regional.png)

### Constituency Analysis
![Constituency Analysis](Images/constituency.png)

---

## Repository Files
- **Power BI file:** [india-election-analysis-2024.pbix](india-election-analysis-2024.pbix)  
- **CSV datasets:** Stored in `Data/` folder (5 files)  
- **Dashboard screenshots:** Stored in `Images/` folder  

---

## 💡 Tools & Technologies
- **Power BI Desktop** – Dashboard creation  
- **Power Query Editor** – Data cleaning and transformation  
- **DAX** – KPI calculations and metrics  
- **Data Modeling** – Relationships between multiple tables  

---

## 🎬 Video Walkthrough
🎥 Watch the 2-minute demo here: [https://1drv.ms/v/c/431b944d5e12f8cb/Efp8kXmFHZBBphs4d3l_TSsBmDB3tvxKAvylfOCicsbbWw?e=SfzXaq]  

---

## 🔍 Insights & Learnings
- NDA held a majority of seats but regional trends vary significantly  
- State-wise and constituency-level drill-through reveals granular insights  
- Demonstrates **end-to-end Power BI workflow**:  
  dataset import → cleaning → modeling → KPI calculation → dashboard creation → drill-through insights  

---

## 🧩 Future Improvements
- Add voter turnout and demographic analysis  
- Integrate official Election Commission datasets for validation  
- Add historical year-over-year comparisons  

---

## 📜 License
MIT License  

---

## 🔗 Connect With Me
LinkedIn: [www.linkedin.com/in/banamali-pradhan]  

