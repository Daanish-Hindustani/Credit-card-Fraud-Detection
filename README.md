# Credit-card-Fraud-Detection

Credit card fraud is a widespread issue driven by evolving cyber threats like identity theft and phishing. This project aims to identify fraud through advanced algorithms and machine learning, enhancing security measures for real-time detection and proactive prevention.

# DataSet
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.

# Stats 
The data set contained a total of Valid:284315 and Fraud:492. This features in this data set included Time,	V1-V28,	Amount, and	Class. 

<img width="765" alt="Screenshot 2024-01-02 at 1 51 29 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/68640865-e12f-4c4f-8ddd-411919212f29">


<img width="439" alt="Screenshot 2024-01-02 at 1 52 23 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/96780088-3b18-4fae-9421-36ddce8eef5f">

<img width="438" alt="Screenshot 2024-01-02 at 1 53 02 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/ecfc2e03-6f87-482f-8836-810ed2020327">

# Model 
RandomForestClassifier was used to determin anomalies in the data and classify fraud vs normal creditcard transactions. The Model was trained on 70% of the training set. No specifc sampling was needed for this model. 

# Results
The model was tested on 30 % of the data and yeilded:
Precision: 0.9556
Accuracy: 0.9995
Recall: 0.7818
F1 Score: 0.8600

<img width="386" alt="Screenshot 2024-01-02 at 2 00 58 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/bc6d196e-5369-4929-a05d-4a6a9d4faa92">


