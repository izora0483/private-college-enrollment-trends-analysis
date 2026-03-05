# 📊 Enrollment Analysis of Private Colleges (IPEDS Case Study)

## Overview
This project analyzes undergraduate enrollment trends across **private, not-for-profit colleges** using data from the **Integrated Postsecondary Education Data System (IPEDS)** from **2018–2023**.

The analysis focuses on how factors such as **tuition, net price, retention, graduation rates, demographics, and institutional characteristics** relate to enrollment patterns across comparable private colleges.  

While the study examines a broad peer group of institutions, there is a **slight focus on Elmhurst University**, as it serves as a reference institution and is the university I currently attend.

This project was completed as part of a **BUS-320 Case Study** at Elmhurst University.

---

## Research Question
How do financial, demographic, and student success factors influence enrollment trends at **small private colleges in the United States**?

---

## Dataset
**Source:**  
Integrated Postsecondary Education Data System (**IPEDS**)  
U.S. Department of Education

Dataset characteristics:

- Institution-level panel data  
- 2018–2023 reporting years  
- 109 comparable institutions  
- Private, nonprofit colleges  
- Primarily undergraduate institutions  
- Enrollment under 10,000 students  

### Variables analyzed
- Fall Enrollment  
- Tuition and Fees  
- Net Price  
- Retention Rate  
- Graduation Rate (150% time)  
- Student–Faculty Ratio  
- Gender Distribution  
- Racial Composition  
- Application Fee Status  

---

## Methodology
The project follows an **exploratory data analysis approach** to understand patterns and relationships within the dataset.

### 1️⃣ Peer Institution Selection
Institutions were filtered using IPEDS attributes to match the profile of **small private undergraduate colleges**.

### 2️⃣ Data Cleaning
- Missing demographic counts treated as zero when appropriate  
- Financial and rate variables left as NA when missing  
- Institutional identifiers verified across years  

### 3️⃣ Feature Engineering
- Created a **POC Majority vs White Majority** institutional classification  
- Aggregated demographic counts to measure racial composition  

### 4️⃣ Trend Analysis
Examined trends over time for:

- Enrollment  
- Retention  
- Graduation  
- Tuition and net price  
- Institutional demographics  

### 5️⃣ Peer Benchmarking
A closer comparison was performed between **Elmhurst University and several larger peer institutions** to understand where it is competitive and where gaps exist.

---

## Key Findings
- Some private colleges experienced **enrollment declines before and during COVID**, followed by partial recovery.
- Institutions with **higher tuition levels often show stronger retention outcomes**.
- **Net price clustering** suggests many colleges strategically discount tuition to remain competitive.
- **Demographic diversity is increasing** across many institutions in the peer group.
- The biggest challenge for many colleges in this segment is **student completion**, not necessarily attracting students.

---


---

## Demo Video
*(Placeholder — demo video will be added soon)*

<!-- Add your demo video link here -->

Example format when ready:


The demo will walk through:

- Dataset overview  
- Key visualizations  
- Enrollment trend findings  
- Peer comparison insights  
- Strategic conclusions  

---

## Tools Used
- **R**
- **IPEDS Data**
- **Excel (Data Preparation)**
- **Power BI Data Visualization**

---

## 📚 Source
U.S. Department of Education, National Center for Education Statistics  
**Integrated Postsecondary Education Data System (IPEDS)**
https://nces.ed.gov/ipeds

