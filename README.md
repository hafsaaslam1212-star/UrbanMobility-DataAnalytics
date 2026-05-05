#  NorthStar Urban Mobility & Logistics Analytics Project

---

##  Overview
This project analyses operational inefficiencies within **NorthStar Urban Mobility and Logistics**, a multi-service transport and delivery system operating across delivery, logistics, and mobile platform services.

The system includes:
- Last-mile delivery operations  
- Hub-based logistics distribution  
- Driver and vehicle management  
- Customer complaint handling  
- Mobile application event tracking  

Despite operational growth, NorthStar experiences increasing performance issues including:
- Delivery delays and failures  
- High customer complaint volumes  
- Inconsistent driver performance  
- Mobile app reliability issues  
- Rising operational costs across zones  

The core issue is **fragmented operational data**, where delivery, customer, driver, and application data are not integrated into a unified analytics system.

---

##  Project Objective
The goal of this project is to design an **integrated data analytics solution** that:

- Identifies operational inefficiencies across zones and hubs  
- Analyses delivery delay and failure patterns  
- Evaluates customer complaints and compensation impact  
- Examines driver behaviour and route efficiency  
- Analyses mobile application reliability issues  
- Implements a NoSQL model for scalable event-based data  

---

##  Key Research Questions
- What zones and hubs experience the highest delivery failure rates?  
- How does driver behaviour (route overrides) affect delivery performance?  
- Which service types generate the highest delays and failures?  
- How are customer complaints distributed across zones and categories?  
- What factors influence mobile app failures and API latency?  

---

##  Technologies Used
- **R (sqldf, dplyr, ggplot2)** → SQL-based analytics, statistical analysis, visualisation  
- **Python (pandas, numpy, matplotlib, seaborn)** → Data cleaning, transformation, feature engineering  
- **MongoDB Atlas** → NoSQL document database design for operational events  
- **Google Colab** → Development and execution environment  
- **GitHub** → Version control and project documentation  

---

##  Workflow

### 1. SQL Analysis (R)
- SQL queries executed using `sqldf`  
- Analysed:
  - Delivery delays and failures  
  - Zone-based performance  
  - Driver employment impact  
  - Service type risk analysis  
- Identified key operational bottlenecks  

---

### 2. Statistical Analysis (R)
- Data manipulation using `dplyr`  
- Visualisation using `ggplot2`  
- Analysed:
  - Delivery status distribution  
  - Complaint trends  
  - Driver behaviour patterns  
  - Route distance vs performance  
- Identified performance gaps across zones  

---

### 3. Data Processing (Python)
- Data cleaning and standardisation  
- Feature engineering:
  - Delivery duration calculation  
  - Delay and failure indicators  
  - Cost per kilometre  
- Dataset preparation for advanced analytics  

---

### 4. NoSQL Database Design (MongoDB)
- Designed document-based collections:
  - **service_reliability_cases** → delivery outcomes + customer ratings  
  - **logistics_activity_logs** → delivery operations by zone  
  - **platform_usage_events** → mobile app events and latency  

- Supports:
  - Nested data structures  
  - Event-driven analytics  
  - Flexible schema design  

---

##  Key Insights (Summary)
- Central, Airport, and East zones show the highest delivery performance issues  
- Delivery delays are the most common operational problem  
- Driver behaviour has a weak but noticeable impact on customer satisfaction  
- Business and Medical service types show high failure risk  
- Mobile app failures and high API latency affect system reliability  
- Customer complaints are strongly linked to delivery delays  

---

##  Solution Approach
The project combines multiple analytical techniques:

- **Relational analysis (SQL in R)** → structured operational insights  
- **Statistical modelling (R)** → trend detection and visualization  
- **Python processing** → data cleaning and feature engineering  
- **NoSQL modelling (MongoDB)** → scalable event-based architecture  

This hybrid approach enables a **360-degree view of logistics operations**, improving decision-making across delivery, customer service, and platform performance.

---

##  Notes
- Data is loaded from Google Drive (`northstar_dataset` folder)  
- Each notebook runs independently  
- MongoDB Atlas is used for cloud-based NoSQL implementation  
- Dataset includes orders, deliveries, drivers, complaints, and app events  

---

##  Conclusion
This project demonstrates how integrating **SQL, R, Python, and MongoDB** can effectively solve real-world logistics problems.

By combining structured and semi-structured data, the system successfully:
- Identifies operational inefficiencies  
- Reveals delivery and complaint patterns  
- Highlights driver and zone performance issues  
- Improves understanding of mobile platform reliability  

Overall, the analysis supports **data-driven decision-making** for improving efficiency, reducing failures, and enhancing customer satisfaction within NorthStar Urban Mobility and Logistics.
