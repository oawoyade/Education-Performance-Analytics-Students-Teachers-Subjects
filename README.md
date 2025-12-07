# 📘 Education Performance Analytics Dashboard  
*A Power BI Business Intelligence Solution for Academic Performance, Student Demographics & Teacher Effectiveness*

## ⭐ Project Overview
The **Education Performance Analytics Dashboard** is a complete end-to-end Power BI solution designed to transform raw academic data into actionable insights. Educational institutions often store large volumes of assessment, demographic and departmental data across disconnected systems. This project solves that challenge by integrating all relevant data into a unified analytical framework powered by **Power BI, DAX, star-schema modelling, and advanced time intelligence**.

The dashboard enables decision-makers to evaluate **student outcomes, subject strengths, teacher performance and demographic patterns** while supporting academic planning, resource allocation and targeted interventions.

---

## 🧠 Key Features

### 🔹 Three Interactive Dashboard Pages
1. **Student Demographics**
2. **Academic Performance Analysis**
3. **Teacher & Subject Effectiveness**

### 🔹 Data Model
- `FactPerformance` — scores, max scores, weighted points, pass/fail  
- `DimStudents` — age, gender, nationality, grade level  
- `DimSubjects` — department, subject names  
- `DimTeachers` — teacher profiles, specialities  
- `DimAssessment` — exam type, weighting, categories  
- `DimDate` — year, term, month, academic calendar

More than **40 DAX measures** were created to calculate:
- Weighted scores  
- Average performance metrics  
- Pass rate % and perfect score %  
- Teacher effectiveness  
- Subject difficulty  
- Student ranking  
- Time intelligence comparisons  

---

## 📊 Insights & Analytics

### 🔹 Student Demographics Summary
- **Total Students:** 50  
- **Pass Rate:** 100%  
- **Average Score:** 70.47%  
- **Assessments Completed:** 18  
- **Average Age:** 16.08 years  

**Grade Level Distribution:**  
- Year 2 → 27 students  
- Year 3 → 12 students  
- Year 1 → 10 students  
- Year 4 → 1 student  

**Nationality Breakdown:**  
- American (12), British (7), Chinese (6), Canadian (5), German (5)

**Gender Breakdown:**  
- Male: 29 (58%)  
- Female: 21 (42%)

---

### 🔹 Academic Performance Highlights
**Top Performing Students:**  
- Louis Dubois — **93.11%**  
- Kenta Kato — **91.68%**  
- Lei Wang — **89.76%**

**Top Performing Subjects:**  
- English Language Arts — **70.17%**  
- Art & Design — **69.78%**  
- Science — **69.07%**  
- Mathematics — **68.86%**

**Performance by Age:**  
- Age 15 → **77.06%**  
- Age 16 → **70.94%**  
- Age 18 → **70.66%**  
- Age 17 → **66.27%**

**Performance by Nationality:**  
- Indian → **84.23%**  
- Korean → **81.92%**  
- Italian → **74.82%**

---

### 🔹 Teacher & Subject Effectiveness
- **Total Teachers:** 5  
- **Total Subjects:** 8  
- **Total Departments:** 8  

**Top Performing Teachers:**  
- Dr. David Brown → **91.30%**  
- Prof. Michael Thompson → **90.68%**  
- Prof. Emma Wilson → **90.17%**

**Weighted Contribution (Balanced):**  
- Emma → 179.42K (25%)  
- Michael → 178.93K (25.16%)  
- Sarah → 176.72K (24.84%)

**Teacher Performance by Nationality:**  
- Indian → **84.43%**  
- Korean → **82.03%**

---

## 🏗️ Technical Stack

| Component         | Technology Used |
|------------------|------------------|
| Data Modelling   | Star Schema      |
| Analytics Engine | DAX              |
| Visualization    | Power BI         |
| Data Prep        | Power Query      |
| Calendar         | Custom DAX table |
| Deployment       | Power BI Desktop |

---

## 📁 Repository Structure

