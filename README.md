Anomaly Detection in 5G Cellular Networks

This project explores the application of machine learning techniques to detect anomalies in 5G cellular networks. 
With the rapid growth of 5G technology, network security has become increasingly critical. 
This system aims to enhance the reliability and security of 5G networks by identifying unusual or potentially harmful behaviors in real time.

Features
Machine Learning Models: 
•	Autoencoders for unsupervised anomaly detection and dimensionality reduction.
•	One-Class SVM to identify deviations from normal network behavior.
•	Random Forest for robust, feature-driven classification.
•	Ensemble techniques combining multiple models for improved accuracy.
Dataset: 
•	A synthetic dataset representing 5G network traffic, including features like timestamps, device types, data usage, and latency.
•	Preprocessed for consistency by handling missing values, normalization, and encoding categorical variables.
Best Model: 
Ensemble 2 (AdaBoost, Decision Tree, ExtraTree) achieved 100% accuracy, demonstrating exceptional performance in anomaly detection.

How It Works
•	Data Preprocessing: The input network traffic data is cleaned, normalized, and encoded to ensure consistency.
•	Model Training: Various machine learning models are trained to learn patterns of normal and anomalous network behaviors.
•	Anomaly Detection: The system analyzes network data in real time and flags unusual behaviors as potential threats.
•	Evaluation: The models are assessed using metrics such as Precision, Recall, Accuracy, and F1 Score to ensure reliability.

Tools and Technologies
•	Programming Language: Python
•	Frameworks: 
Flask for building the user interface.
Jupyter Notebook for development and testing.
•	Libraries: 
Scikit-learn for machine learning algorithms.
Pandas and NumPy for data manipulation.
Matplotlib for visualizations.

Highlights
The project integrates advanced ensemble techniques to enhance the accuracy and robustness of anomaly detection.
Real-time anomaly detection capabilities ensure timely intervention and mitigation of potential threats.
The system provides a scalable and adaptive solution for monitoring complex and high-traffic 5G environments.

Contributors
Musunuru Shamitha
Vannempalli Sanvika
Madala Poorna Chandra

Supervisor: Dr. Indrasen Singh

