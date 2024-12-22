# Telecom Customer Usage Analysis

## **Overview**
This project performs a comprehensive analysis of telecom customer usage data to derive insights into user engagement, experience, and satisfaction. The dataset includes key metrics such as session duration, data traffic, device information, and network parameters, enabling a multi-dimensional exploration of customer behavior.

The analysis encompasses:
- Engagement Analysis
- Experience Analysis
- Satisfaction Analysis
- Clustering for user segmentation

---

## **Features**

### **1. Engagement Analysis**
- Metrics: Session frequency, session duration, and total data traffic.
- Tasks:
  - Top 10 customers for each engagement metric.
  - K-Means clustering to group users based on engagement.
  - Segmentation and visualization of high, medium, and low-engaged users.

### **2. Experience Analysis**
- Metrics: TCP retransmission, RTT (Round Trip Time), throughput, and handset type.
- Tasks:
  - Aggregation of user experience metrics.
  - Distribution and summary statistics for each network parameter.
  - K-Means clustering to segment users based on network experience.
  - Insights into device-specific performance.

### **3. Satisfaction Analysis**
- Combines engagement and experience metrics to evaluate user satisfaction.
- Tasks:
  - Calculation of engagement and experience scores using Euclidean distance.
  - Satisfaction score: The average of engagement and experience scores.
  - Regression modeling to predict satisfaction scores.
  - K-Means clustering of users based on satisfaction metrics.
  - Export of the final dataset to a MySQL database.

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Database Interaction: `pymysql`, `SQLAlchemy`
- **Database**: MySQL

---

## **Setup Instructions**

### **1. Prerequisites**
- Python 3.8+ installed.
- MySQL server running locally or remotely.
- Required Python libraries installed:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn pymysql sqlalchemy
