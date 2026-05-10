# NorthStar Urban Mobility & Logistics Analytics Project

---

## Overview

This project investigates operational inefficiencies within NorthStar Urban Mobility and Logistics, a multi-service transport and delivery system operating across delivery, logistics, and mobile platform services.

The organisation manages last-mile deliveries, hub-based logistics distribution, driver and vehicle operations, customer complaint handling, and mobile application event tracking.

Despite continued operational growth, the system faces significant performance challenges including delivery delays and failures, high customer complaint volumes, inconsistent driver performance, mobile application reliability issues, and rising operational costs across different zones. The core issue is fragmented operational data, where delivery, customer, driver, and application datasets are stored in isolation and are not integrated for unified analysis.

---

## Project Objective

The objective of this project is to design and implement an integrated data analytics solution capable of identifying inefficiencies across the organisation.

The system focuses on analysing delivery delay and failure patterns, evaluating customer complaints and compensation impacts, assessing driver behaviour and route efficiency, and examining mobile application reliability.

In addition, the project introduces a NoSQL-based model for scalable event processing and incorporates distributed computing using Apache Spark to efficiently handle large-scale logistics data.

---

## Key Research Questions

This study addresses the following analytical questions:

- Which zones and hubs experience the highest delivery failure rates?
- How does driver behaviour (e.g., route overrides) affect delivery performance?
- Which service types generate the highest delays and failures?
- How are customer complaints distributed across zones and categories?
- What factors influence mobile application failures and API latency?

---

## Technologies Used

The project integrates multiple technologies to support end-to-end analytics.

R is used for SQL-based analysis, statistical modelling, and data visualisation. Python is used for data cleaning, transformation, and feature engineering using libraries such as pandas and NumPy.

Apache Spark (PySpark) is used for distributed processing of large-scale logistics datasets. MongoDB Atlas is used for NoSQL document-based storage design. Google Colab serves as the development environment, while GitHub is used for version control and documentation.

---

## Workflow

The analysis begins with SQL-based processing in R, where structured queries are used to analyse delivery delays, failure patterns, zone-level performance, and driver impact. This provides a structured understanding of operational inefficiencies.

Statistical analysis is then performed in R using dplyr and ggplot2 to explore complaint trends, performance variations across zones, and relationships between operational variables.

Python is used for data preprocessing and feature engineering, including calculation of delivery durations, delay indicators, and cost efficiency metrics.

Apache Spark is then introduced to handle large-scale distributed processing. Using PySpark, delivery datasets are loaded from Google Drive and processed as DataFrames. Spark enables efficient zone-wise and driver-wise aggregation, significantly improving performance over traditional single-machine processing.

Finally, MongoDB is used to implement a NoSQL architecture. Collections such as service reliability cases, logistics activity logs, and platform usage events are designed using document-based structures to support nested data and event-driven analytics.

---

## Key Insights

The analysis shows that Central, Airport, and East zones experience the highest delivery performance issues. Delivery delays are identified as the most frequent operational problem.

Driver behaviour has a moderate impact on customer satisfaction, while Business and Medical service types demonstrate higher failure risk.

Mobile application latency and system failures negatively affect overall system reliability. A strong correlation is observed between delivery delays and customer complaints, highlighting the direct impact of operational inefficiencies on customer experience.

---

## Solution Approach

The project adopts a hybrid analytics approach combining multiple technologies.

Relational analysis in R is used for structured insights, Python is used for data engineering, Apache Spark enables distributed processing, R supports statistical visualisation, and MongoDB provides scalable NoSQL storage.

This integrated architecture enables a 360-degree analytical view of logistics operations and supports data-driven decision-making.

---

## Conclusion

This project demonstrates how the integration of SQL, R, Python, Apache Spark, and MongoDB creates a scalable and efficient big data analytics ecosystem.

The system successfully identifies operational inefficiencies, reveals delivery and complaint patterns, improves understanding of driver and zone performance, and enhances visibility of mobile application reliability.

Overall, the hybrid architecture combining distributed processing and multi-paradigm analytics provides a strong foundation for advanced decision-making in complex logistics environments such as NorthStar Urban Mobility and Logistics.
