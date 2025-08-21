# 🏀 NBA Superstar ROI Case Study

## 📌 Project Overview
This project analyzes whether the NBA’s highest-paid players are **overpaid, fairly paid, or underpaid** relative to their on-court productivity.  
By combining **salary data** with **player performance stats**, I built a custom **Fantasy Points ROI model** to evaluate the **return on investment (ROI)** of each player.

---

## 🔍 Key Questions
- Do higher salaries correlate with higher productivity?  
- Which players are delivering *maximum ROI* (underpaid for their output)?  
- Which players are *overvalued* based on mediocre performance?  
- How can we visualize and communicate value vs cost in a business context?  

---

## 🛠 Data Sources
- **Salary Data:** 2025–26 NBA contracts (top 30 players)  
- **Player Stats:** 2023–24 per-game averages (points, rebounds, assists, steals, blocks, turnovers)  
- **Derived Metrics:** Fantasy Points & ROI  

---

## 📊 Methodology & Calculations
1. **Fantasy Points Formula** (weighted all-around performance metric):  

Fantasy Points = (PTS × 1) + (AST × 1.5) + (REB × 1.2)
+ (STL × 3) + (BLK × 3) – (TOV × 1)


2. **League Averages for Benchmarking**  
- Average Fantasy Points ≈ 43  
- Average Superstar Salary ≈ $49M  

Players above 43 FP are considered strong performers; below 43 FP are weaker performers.

3. **Value Classification Rules**  

If Fantasy Points > 43 and Salary < $49M → Underpaid (Good Value ✅)
If Fantasy Points ≈ 43 and Salary ≈ $49M → Fairly Paid ⚖️
If Fantasy Points < 43 and Salary > $49M → Overpaid (Bad Value ❌)

4. **Return on Investment (ROI)**  
Productivity per million dollars of salary:  

ROI = Fantasy Points ÷ (Salary ÷ 1,000,000)


Example:  
- Player with 50 FP and $50M salary → ROI = 50 ÷ 50 = **1.0 FP per $1M**  
- Higher ROI means **more production for less cost**.

---

## 📈 Visuals
- **Scatter Plot:** Salary vs Productivity (color-coded for over/under/fair value).  
- **Bar Chart:** Fantasy Points by Player (raw performance).  
- **ROI Chart:** Productivity per $1M salary (true value metric).  

---

## 💡 Key Findings
- **Luka Dončić & Nikola Jokić** = *most efficient superstars*, producing far above what their salaries suggest.  
- Some of the NBA’s **highest-paid veterans** show mediocre ROI → *overvalued contracts*.  
- ROI analysis proves that **spending more doesn’t guarantee performance** — a direct parallel to **business ROI and resource allocation**.  

---

## 🧑‍💻 Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  

---

## 🚀 Why It Matters
This project demonstrates how **data analytics can reveal inefficiencies in high-stakes investments**.  
While the subject is basketball, the methodology applies to **business intelligence, workforce efficiency, and ROI optimization** across industries.  

---

📌 *Analysis & Visualization by Jehlyen Fuller Connect with me on LinkedIn: https://www.linkedin.com/in/jehlyen-fuller-83bb89323/*  
