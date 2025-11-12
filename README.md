# Predictive Dashboard Design Using Random Forest and Streamlit
### Case Study: IT Procurement Contract Monitoring at Bank XYZ

This repository presents the implementation and documentation of a **predictive web-based dashboard system** designed to monitor **IT procurement contracts** at Bank XYZ.  
The project applies **machine learning (Random Forest)** and **interactive visualization (Streamlit)** to improve **IT governance** and reduce the risk of missed contract renewals.

---

## Project Objective
To design and develop a **predictive analytics dashboard** that automates the classification of IT contract risks based on contract duration and expiration date.  
The system provides **interactive visualization** and **high-risk notifications**, enabling the IT Division to monitor contracts proactively and support **data-driven decision-making**.

---

## Role: System Analyst & Business Analytics
- Conducted **business process analysis** and identified inefficiencies in manual contract tracking (Excel-based).  
- Defined **system requirements** and functional specifications using **SDLC (Waterfall)** methodology.  
- Designed the **system architecture**, **use case diagram**, and **data flow model**.  
- Implemented predictive classification using **Random Forest** integrated with **Streamlit** and **Google Sheets**.  
- Conducted **system evaluation** through accuracy metrics and user feedback from the IT PMA team.

---

## Methodology: SDLC (Waterfall Model)

1. **Planning:** Identified pain points in the manual monitoring workflow.  
2. **Analysis:** Mapped the as-is process, performed **root cause analysis** using a Fishbone diagram.  
3. **Design:** Developed system architecture and user interface wireframes.  
4. **Implementation:** Built the Streamlit dashboard with Python and integrated the Random Forest model.  
5. **Testing & Evaluation:** Conducted user testing, confusion matrix evaluation, and cross-validation.

---

## Tools & Technologies

| Category | Tools |
|-----------|-------|
| Programming | Python, Streamlit |
| Machine Learning | Scikit-learn, Random Forest, SMOTE, RandomizedSearchCV |
| Data Handling | Pandas, NumPy, Google Sheets API |
| Model Deployment | Joblib, Streamlit Cloud |
| Visualization | Matplotlib, Seaborn |
| Communication & Notification | SMTP Email Integration |
| Design & Documentation | Lucidchart, Draw.io |
| Methodology | SDLC (Waterfall) |

---

## System Features
- 🔹 **Predictive Classification** — Contract risk level: *High*, *Medium*, *Low* using Random Forest.  
- 🔹 **Dual-Model System** — Comparison between *rule-based* and *machine learning*-based classification.  
- 🔹 **Interactive Dashboard** — Contract filtering by vendor, type, and risk category.  
- 🔹 **Visualization & Reporting** — Charts and “Top 50 High-Priority Contracts” table.  
- 🔹 **Email Notification System** — Automatic alerts for expiring or high-risk contracts.  
- 🔹 **Google Sheets Integration** — For both input and output data management.

---

## Results & Evaluation

| Model | Accuracy | F1 (Low) | F1 (Medium) | F1 (High) | Rule-Based Alignment |
|--------|-----------|-----------|--------------|------------|----------------------|
| Random Forest (Iteration 2) | 81.7% | 0.64 | 0.62 | 0.89 | 82.7% |
| Random Forest (Iteration 4) | 68.3% | 0.60 | 0.45 | 0.77 | **92.3%** |

- **Strong correlation (r = 0.71)** between contract value and priority classification.  
- Random Forest model demonstrated **reliable predictive accuracy** and consistent results across validation sets.  
- User evaluation confirmed **dashboard usability** and **relevance to operational workflow**.  

---

## System Architecture Overview
**Core Components:**
1. **Data Input Module** – Connects to Google Sheets and retrieves contract datasets.  
2. **Preprocessing Module** – Performs label encoding, SMOTE balancing, and noise injection.  
3. **Classification Engine** – Executes both Rule-Based and Random Forest prediction models.  
4. **Visualization & Alert Module** – Displays results on Streamlit dashboard and sends email alerts.  
5. **Output Module** – Stores predictions and evaluation results back to Google Sheets.

---

## Key Contributions
- Designed and implemented an **end-to-end predictive contract monitoring system** aligned with IT governance principles.  
- Demonstrated **integration of business rules and machine learning** for practical decision support.  
- Enhanced **visibility and control** over procurement contracts within Bank XYZ’s IT Division.  
- Provided **academic and operational insights** for digital transformation in contract management.  

---

## Documentation 
- [Research Poster (Conference Version)](poster/Poster.jpg)  

---

## Conclusion
This project successfully bridges **Business Analytics** and **System Analysis**, demonstrating how predictive analytics can be embedded into operational workflows through structured system design.  
The resulting dashboard offers a practical model for **data-driven decision support**, applicable to future IT governance, ERP monitoring, and procurement systems.

> _“Transforming business insights into actionable systems through analytics and design.”_

---

