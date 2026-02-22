# 🏏 IPL Data Analytics Magazine | End-to-End BI Project

## 🔗 Live Dashboard
https://app.powerbi.com/view?r=eyJrIjoiYzEwNGU3OWQtNjc1Mi00Y2FkLWJkZGQtYjcyYTFiOGUzMjkxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9
---

# 🏢 Business Problem

Cricket performance analysis is often limited to raw statistics (runs, wickets, averages).  
However, management-level insights require contextual metrics such as:

- Qualification-based performance filters
- Pressure-based win %
- Chasing vs defending impact
- Multi-season performance comparison
- Role-balanced team selection logic

The objective was to design a complete analytical magazine-style dashboard that transforms match-level data into strategic cricket intelligence.

---

# 🎯 Project Objective

To build an end-to-end IPL analytics solution that:

- Evaluates batting & bowling performance with qualification logic
- Analyzes team performance under match pressure
- Compares last 3 seasons trends
- Identifies Top 4 qualification patterns
- Predicts 2024 award winners & Best Playing XI
- Presents insights through interactive storytelling

---

# 📊 Dashboard Modules

## 1️⃣ Batting Analysis
- Total Runs
- Strike Rate
- Batting Average
- Boundary %
- Minimum balls qualification logic
- Season-wise comparison

## 2️⃣ Bowling Analysis
- Wickets
- Economy Rate
- Bowling Average
- Dot Ball %
- Performance consistency filters

## 3️⃣ Team Performance Analysis
- Chasing vs Defending Win %
- Pressure Win %
- Top 4 Qualification trends
- 3-Year Comparative Analysis
- Match outcome logic

## 4️⃣ 2024 Predictions Engine
- Orange Cap Prediction
- Purple Cap Prediction
- Best Playing XI (Role-balanced model)
- Based on 3-year weighted performance

---

# 📈 Key Business Insights

- High strike rate does not always correlate with match-winning impact
- Chasing teams show higher win % under moderate pressure scenarios
- Certain bowlers dominate in death overs despite lower overall wickets
- Team consistency over 3 seasons strongly influences Top 4 probability
- Balanced role distribution is critical for Best XI optimization

---

# 🧠 Business Logic Implemented

- Minimum balls qualification for batting rankings
- Chasing vs defending identification logic
- Pressure scenario classification
- 3-year weighted performance scoring
- Role-based XI selection model

---

# 🛠 Technical Implementation

- Star Schema Data Model (Fact + Dimension)
- Advanced DAX:
  - CALCULATE()
  - FILTER()
  - ALL()
  - SELECTEDVALUE()
  - Time Intelligence
- Context Transition Handling
- Dynamic Ranking Measures
- KPI Conditional Formatting
- Interactive Drill-through & Filters

---

# 🧩 Data Pipeline

Excel → Power Query → Cleaned Model → DAX Measures → Interactive Dashboard

---

# 🧠 Skills Demonstrated

✔ Sports Data Analytics  
✔ Advanced DAX & Context Handling  
✔ Business Rule Engineering  
✔ Predictive Logic Modeling  
✔ Performance Benchmarking  
✔ Data Storytelling  
✔ UX-Focused Dashboard Design  
