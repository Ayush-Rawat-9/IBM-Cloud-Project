# IBM-Cloud-Project
IBM cloud project details and files.

# Problem statement – Predictive Maintenance of Industrial Machinery 
Develop a predictive maintenance model for a fleet of industrial machines to anticipate 
failures before they occur. This project will involve analyzing sensor data from machinery 
to identify patterns that precede a failure. The goal is to create a classification model that 
can predict the type of failure (e.g., tool wear, heat dissipation, power failure) based on 
real-time operational data. This will enable proactive maintenance, reducing downtime 
and operational costs.

# Dataset
Kaggle dataset link – https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification

# Solution 
The Random Forest Classifier in IBM Watson Studio's AutoAI environment was used to create the 
predictive maintenance model, which performed exceptionally well. Across all failure categories, the 
model's precision, recall, and F1-scores were all high. The model's ability to categorize failure categories 
like tool wear, heat loss, and power failure was validated by evaluation metrics and visualizations like the 
confusion matrix and feature importance plot. With IBM Watson Machine Learning, the finished model 
was effectively implemented as a REST API for real-time prediction.

# Resources Used
IBM Cloud Object Storage & Watson Machine Learning – IBM Cloud Services.
