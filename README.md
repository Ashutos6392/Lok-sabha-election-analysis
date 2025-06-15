# 🇮🇳 Lok Sabha Election Data Analysis (2014 vs 2019)

A comprehensive data analysis project comparing the **2014 and 2019 Indian General Elections**, enriched with additional datasets like **GDP by state** and **literacy rates** to uncover deeper socio-political patterns.

## 📁 Datasets Used

1. **constituency_wise_results_2014 (CSV)**
2. **constituency_wise_results_2014(CSV)**  

3. **External DataSet**
- GDP by State (2014 & 2019)
- Literacy Rate by State (2011 Census)
## 🧹 Data Cleaning & Transformation

Cleaning was essential due to:
- **Spelling mismatches** in states/party names
- **Missing or inconsistent values**
- **Bifurcation Issue (Andhra Pradesh & Telangana):**
- In 2014, Telangana was not yet a separate state.
- Constituencies like *Hyderabad*, *Warangal*, and *Adilabad* were listed under Andhra Pradesh.
- Using `Python (Pandas)`, these were reassigned to Telangana for correct comparison.

- ## 🔍 Analytical Highlights

### 🗳️ Voter Turnout Analysis
- Calculated **voter turnout %** per constituency and state.
- Compared voter turnout in **2014 vs 2019**.

### 📈 Top/Bottom Rankings
- **Top 5 and Bottom 5 Constituencies** by voter turnout ratio (2014 & 2019)
- **Top 5 and Bottom 5 States** by voter turnout ratio (2014 & 2019)

### 🔁 Voting Behavior Changes
- **Constituencies that elected the same party** in both 2014 and 2019, ranked by **% vote share in 2019**
- **Constituencies that switched parties**, listing **Top 10 constituencies** with most dramatic party change

### 👥 Candidate-Level Analysis
- **Top 5 candidates** with the **largest margin of victory** over runner-ups

### 📊 Party Vote Share Analysis
- **% Vote Split of Parties at National Level** (2014 vs 2019)
- **% Vote Split of Parties at State Level** (2014 vs 2019)

### ⚠️ NOTA (None of the Above)
- **Constituencies with the highest NOTA votes**

### 📉 Correlation Studies
- **Literacy Rate vs Voter Turnout %**
- **GDP of State vs Voter Turnout %**

---

## 📊 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Power BI / Tableau** (Dashboard & Visualization)
- **Excel** (Initial data review & formatting)

---

## 🖼️ Project Deliverables
📄 [View Dashboard (PDF)](dashboard.pdf)
