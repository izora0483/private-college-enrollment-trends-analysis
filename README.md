# Elmhurst Enrollment Analysis: IPEDS Case Study

## Overview
This project analyzes undergraduate enrollment trends at **Elmhurst University** compared to similar **private, not-for-profit institutions** using data from the **Integrated Postsecondary Education Data System (IPEDS)** between **2018 and 2023**.

The goal of the analysis is to understand how factors such as **tuition, net price, retention, graduation rates, demographics, and institutional characteristics** relate to enrollment patterns across comparable universities.

The project was completed as part of a **BUS-320 Case Study** at Elmhurst University.

---

## Research Question
How do financial, demographic, and student success factors influence enrollment trends at private, not-for-profit universities similar to Elmhurst?

---

## Dataset
Source:  
**Integrated Postsecondary Education Data System (IPEDS)**  
U.S. Department of Education

Dataset characteristics:
- Institution-level panel data
- 2018–2023 reporting years
- 109 comparable institutions
- Private, nonprofit universities
- Primarily undergraduate institutions
- Enrollment under 10,000 students

Variables analyzed include:

- Fall Enrollment
- Tuition and Fees
- Net Price
- Retention Rate
- Graduation Rate (150% time)
- Student-Faculty Ratio
- Gender Distribution
- Racial Composition
- Application Fee Status

---

## Methodology
The analysis follows an exploratory data analysis approach:

1. **Peer Institution Selection**
   - Filtered institutions using IPEDS attributes to match Elmhurst’s profile.

2. **Data Cleaning**
   - Missing demographic counts treated as zero when appropriate.
   - Financial and rate variables left as NA when missing.
   - Institutional identifiers verified across years.

3. **Feature Engineering**
   - Created **POC Majority vs White Majority** institutional classification.
   - Aggregated demographic counts to measure racial composition.

4. **Trend Analysis**
   - Examined enrollment, retention, graduation, pricing, and demographic trends over time.

5. **Peer Benchmarking**
   - Compared Elmhurst with top benchmark institutions:
     - Merrimack College
     - Roger Williams University
     - Siena College

---

## Key Findings
- Elmhurst experienced **modest enrollment growth** while many comparable institutions declined.
- **Retention rates are close to peer averages**, but **graduation rates lag behind leading institutions**.
- Elmhurst maintains a **significant net price advantage** relative to similar universities.
- The student body is becoming **increasingly diverse**, with students of color approaching half of undergraduate enrollment.
- The largest strategic opportunity for Elmhurst is **improving student completion outcomes** rather than increasing enrollment.

---


---

## Demo Video
*(Placeholder — demo video will be added soon)*

<!-- Add your demo video link here -->

Example format when ready:
https://youtu.be/your-demo-video


The demo will walk through:

- Dataset overview
- Key visualizations
- Enrollment trend findings
- Peer comparison insights
- Strategic conclusions

---

## Tools Used

- **R**
- **RStudio**
- **IPEDS Data**
- **Excel (Data Preparation)**
- **Exploratory Data Visualization**

---

## Author
**Inaya Zoraiz**  
Elmhurst University  
Economics & Information Systems

---

## Source
U.S. Department of Education, National Center for Education Statistics.  
Integrated Postsecondary Education Data System (IPEDS)

https://nces.ed.gov/ipeds
