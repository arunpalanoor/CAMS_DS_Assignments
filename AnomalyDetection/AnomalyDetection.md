# Anomaly Detection

An anomaly-also known as an outlier-is an observation that significantly deviates from the expected pattern or statistical distribution within a dataset. Detecting such anomalies is critical in real-world applications, where they can either obscure insights or reveal hidden signals.
From a strategic standpoint, anomalies can be interpreted in two distinct ways:
- As disruptive outliers: These can distort analytical models, compromise data integrity, and hinder reliable decision-making.
- As informative signals: When treated as meaningful deviations, anomalies can uncover latent patterns, flag emergent risks, or predict unexpected behaviors—transforming noise into actionable intelligence.

This repository contains my experimental use cases using various anomaly detection methods.
Datasets are sourced from https://www.kaggle.com/

## Real world use cases:

### 🏭 Manufacturing & Industry
- Predictive Maintenance: Spotting unusual vibration, temperature, or pressure readings in machines to prevent breakdowns.
- Quality Control: Detecting defective products on an assembly line by identifying outlier measurements.
- Supply Chain Monitoring: Finding anomalies in logistics data, like unexpected delays or unusual shipping routes.

### 🏥 Healthcare
- Patient Monitoring: Detecting irregular heartbeats, oxygen levels, or blood pressure in real time.
- Medical Imaging: Identifying unusual patterns in X-rays, MRIs, or CT scans that may indicate rare conditions.
- Epidemiology: Spotting unusual spikes in disease cases that could signal an outbreak.

### 💳 Finance & Banking
- Fraud Detection: Spotting unusual credit card transactions (e.g., sudden large purchases in a foreign country).
- Anti-Money Laundering (AML): Identifying suspicious transaction patterns that don’t match a customer’s profile.
- Trading Surveillance: Detecting irregular stock trades that may indicate insider trading or market manipulation.

### 🛒 Retail & E-commerce
- Customer Analytics: Identifying unusual shopping behavior that may indicate fraud.
- Inventory Management: Spotting anomalies in sales data to prevent overstocking or stockouts.
- Recommendation Systems: Filtering out unusual data points that could skew recommendations.

### 🌐 Cybersecurity & IT
- Network Intrusion Detection: Flagging abnormal spikes in traffic that could signal a cyberattack.
- User Behavior Analytics: Detecting unusual login times, locations, or access patterns.
- System Monitoring: Identifying server performance anomalies before outages occur.


## Statistical Methods

### Z-Score
Z score tells how far the observation is compared to the mean
- Use it only for Gaussian distribution
- Only for single variable/feature
- Cannot be used for Multi modal (cases with more than 1 class of data)
- Cannot be used for skewed data set
Sample projects:
https://github.com/arunpalanoor/CAMS_DS_Assignments/blob/main/AnomalyDetection/AutomotiveEngineHealth_Analysis.ipynb


### IQR (Interquartile range)

## Unsupervised Machine Learning Algorithms

### k-means clustering

### Support vector machines (SVM)

### Isolation Forest
