# abap-lsmw-data-migration
SAP ABAP project using LSMW for customer master data migration


## 📌 Project Overview

This project demonstrates how to use **LSMW (Legacy System Migration Workbench)** and **ABAP routines** to migrate customer master data into SAP ERP. It's designed for data migration scenarios where large amounts of structured data must be imported cleanly and efficiently.

---

## 🛠️ Tools & Technologies

- SAP ECC
- LSMW
- ABAP
- Excel (for source data)
- SAP GUI
- TCodes: `LSMW`, `SE38`, `SE11`, `SE80`

---

## 🧠 Key Features

- Mapping source fields to SAP structures
- Using ABAP for field-level transformations and validations
- Importing customer master data through batch input
- Handling errors and logs during migration
- Custom reusable LSMW object

---

## 📂 Folder Structure



---

## 🖼️ Screenshots & Diagrams


- LSMW project creation
- Field mapping screen
- ABAP routine window
- Batch input execution
- Logs or reports

---

## 🚀 How to Use (Summary)

1. Prepare a structured Excel file with customer data
2. In SAP, create a new **LSMW project**, **subproject**, and **object**
3. Define source structure, source fields, and relationships
4. Map source fields to SAP target fields
5. Write ABAP routines for field transformation (optional but recommended)
6. Execute LSMW steps in order:
   - Read Data
   - Convert Data
   - Display Converted Data
   - Create Batch Input Session
   - Run Batch Input Session
7. Check logs for errors and success

---

## 🎓 What I Learned

- Designing and structuring LSMW objects from scratch
- Writing ABAP transformation logic for incoming data
- Handling batch input sessions and troubleshooting common issues
- Understanding real-world data cleansing and validation requirements
- The importance of test runs and logs before final execution

---

## 🧩 Related Topics

- Modularization in ABAP for reusable code
- BAPIs vs. Batch Input in data migration
- Customer master tables: `KNA1`, `KNVV`, `KNB1`

---

## 📫 Contact

Have feedback or questions?  
Reach out via my  or email me at: `your.email@example.com`

---

> 🧩 This is part of my **SAP ABAP Developer Portfolio**. Explore more projects on my [GitHub profile](https://github.com/kalaivaninishan).

