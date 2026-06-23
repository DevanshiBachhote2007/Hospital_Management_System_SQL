# 🏥 Hospital Management System (SQL Project)

> A comprehensive SQL-based project to manage hospital operations including patients, doctors, appointments, medical records, billing, and departments.  
> Demonstrates CRUD operations, SQL clauses, joins, subqueries, aggregate functions, window functions, and case expressions in a real-world healthcare context.

---

## 📌 Table of Contents
- 📖 Overview
- 📂 Project Files
- 🗂 Database Schema
- 🛠 Tools & Technologies
- 📐 Project Structure
- 🎯 Project Purpose
- ⚙️ Implemented Features
- 🔄 Analysis Workflow
- 📊 Key Insights
- 🌍 Impact & Importance
- ▶️ How to Run
- ✅ Conclusion
- 👩‍💻 Author

---

## 📖 Overview
This project simulates a **Hospital Management System** using SQL.  
It covers the end-to-end workflow of hospital operations:  
- Patient registration and doctor allocation  
- Appointment scheduling and tracking  
- Medical record management  
- Billing and payment tracking  
- Departmental organization of doctors  

---

## 📂 Project Files
- `Hospital_Management.sql` – Main SQL script with schema, inserts, and queries.  
- `README.md` – Documentation explaining schema, queries, and insights.  

---

## 🗂 Database Schema
The project includes the following tables:  
- **Patients** – Patient details and registration info  
- **Doctors** – Doctor details, specialization, and fees  
- **Appointments** – Patient-doctor appointments with status  
- **Medical_Records** – Diagnosis, prescriptions, and treatments  
- **Billing** – Invoice, payment status, and amounts  
- **Departments** – Hospital departments  
- **Doctor_Department** – Mapping between doctors and departments  

---

## 🛠 Tools & Technologies
- SQL (DDL, DML, Joins, Subqueries, Window Functions)  
- MySQL / PostgreSQL (compatible)  
- Relational Database concepts  

---

## 📐 Project Structure
```text
Hospital_Management/
├── Hospital_Management.sql
└── README.md
```
---

## 🎯 Project Purpose
The purpose of this project is to:
* **Design and implement** a relational database system tailored for healthcare environments.
* **Practice essential SQL operations** including CRUD, joins, grouping, aggregate functions, and window functions.
* **Provide a real-world case study** of hospital workflows using structured queries.
* **Deliver an easy-to-understand analysis** for students, developers, and GitHub viewers.

---

## ⚙️ Implemented Features
* **CRUD Operations** – Insert, update, and delete records for patients, doctors, and appointments.
* **Clauses & Operators** – Filtering, sorting, grouping, and applying logical conditions.
* **Aggregate Functions** – Utilizing `SUM`, `AVG`, and `COUNT` for tracking revenue and doctor visits.
* **Joins** – Performing `INNER`, `LEFT`, `RIGHT`, and `UNION` joins across multiple tables.
* **Subqueries** – Implementing nested queries for advanced and precise filtering.
* **Date & Time Functions** – Extracting appointment months, formatting treatment dates, and calculating stay durations.
* **String Manipulation** – Formatting data using uppercase transformation, trimming, and value replacement.
* **Window Functions** – Ranking doctors by patient volume and calculating running revenue totals.
* **CASE Expressions** – Categorizing patient risk levels and classifying doctors by experience.

---

## 🔄 Analysis Workflow
1. **Schema Creation:** Define tables with proper primary and foreign key constraints.
2. **Data Ingestion:** Insert sample records for patients, doctors, appointments, and billing.
3. **Operational Queries:** Execute analytical queries to investigate hospital workflows.
4. **Insight Generation:** Analyze metrics surrounding revenue, doctor workloads, patient risk levels, and departmental efficiency.
5. **Advanced Analytics:** Apply window functions and conditional CASE logic for deeper analysis.

---

## 📊 Key Insights
* **Revenue Tracking** – Computes total hospital earnings directly from billing records.
* **Doctor Workload** – Employs ranking systems to evaluate the number of patients handled per doctor.
* **Departmental Analysis** – Breaks down overall financial and revenue contributions per department.
* **Patient Risk Levels** – Categorizes patient vulnerability profiles based on underlying medical records.
* **Doctor Categorization** – Classifies medical staff into *Junior*, *Mid-Level*, and *Senior* tiers based on experience.
* **Operational Efficiency** – Pinpoints problem areas by tracking cancelled appointments and outstanding pending payments.

---

## 🌍 Impact & Importance
* **Healthcare Efficiency** – Demonstrates how SQL database management can streamline complex hospital workflows.
* **Data-Driven Decisions** – Empowers healthcare administrations to systematically track revenue, patient care quality, and staff allocation.
* **Scalability** – Structured to easily scale for larger datasets or integrate into live healthcare application backends.
* **Educational Value** – Serves as a modular, hands-on portfolio project for students and professionals learning database design.

---

## ▶️ How to Run
1. Open your preferred SQL IDE or environment (e.g., MySQL Workbench, PostgreSQL/pgAdmin).
2. Copy and execute the core schema script: `Hospital_Management.sql`.
3. Run the analytical queries section by section (CRUD, clauses, joins, window functions, etc.).
4. Observe the tabular outputs to interpret operational trends.

---

## ✅ Conclusion
This project presents a robust SQL case study for hospital management operations, illustrating how a relational database can elegantly handle healthcare data from initial patient registration down to final billing. By bridging foundational concepts with advanced analytical techniques, this repository highlights the vital role structured data plays in modern healthcare management.

---

## 👩‍💻 Author
**Devanshi Bachhote**

