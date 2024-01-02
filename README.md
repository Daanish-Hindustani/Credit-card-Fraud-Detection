# Credit-card-Fraud-Detection

# Introduction
Addressing the pervasive issue of credit card fraud necessitates cutting-edge solutions due to evolving cyber threats, such as identity theft and phishing. This project is dedicated to implementing machine learning methodologies for the identification and prevention of credit card fraud, with a focus on enhancing security measures through real-time detection and proactive measures.

# Dataset
The dataset employed in this project was meticulously collected and analyzed through a collaborative effort between Worldline and the Machine Learning Group at ULB (Université Libre de Bruxelles). The research collaboration aimed to explore big data mining and fraud detection, providing a rich dataset for our analysis.

# Dataset Statistics
The dataset comprises a total of 284,315 valid transactions and 492 fraudulent transactions. Key features include Time, V1-V28, Amount, and Class. Understanding the intricacies of this dataset was crucial for developing effective fraud detection models.


<img width="765" alt="Screenshot 2024-01-02 at 1 51 29 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/68640865-e12f-4c4f-8ddd-411919212f29">


<img width="439" alt="Screenshot 2024-01-02 at 1 52 23 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/96780088-3b18-4fae-9421-36ddce8eef5f">

<img width="438" alt="Screenshot 2024-01-02 at 1 53 02 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/ecfc2e03-6f87-482f-8836-810ed2020327">


# Model Development
The RandomForestClassifier was selected for its suitability in identifying anomalies and classifying transactions as fraudulent or normal. The model underwent training on 70% of the dataset, and it's noteworthy that no specific sampling techniques were deemed necessary for achieving robust results.

# Challenges Overcome
Imbalanced Dataset:
Addressing the imbalanced nature of the dataset, with a significantly higher number of valid transactions compared to fraudulent ones, posed a challenge. Employing techniques such as oversampling, undersampling, or using ensemble methods helped mitigate this issue.

# Feature Selection:
Determining the most relevant features for the model was critical. Features like Time, V1-V28, and Amount were carefully analyzed to ensure their contribution to accurate fraud detection.

# Model Evaluation:
Evaluating the model's performance required a nuanced approach. Metrics such as precision, accuracy, recall, and F1 score were considered comprehensively to gauge the model's effectiveness in real-world scenarios.

# Results
After rigorous training and testing, the model demonstrated robust performance:

Precision: 0.9556
Accuracy: 0.9995
Recall: 0.7818
F1 Score: 0.8600

<img width="386" alt="Screenshot 2024-01-02 at 2 00 58 PM" src="https://github.com/Daanish-Hindustani/Credit-card-Fraud-Detection/assets/134811343/bc6d196e-5369-4929-a05d-4a6a9d4faa92">

# Conclusion
This project represents a significant step forward in credit card fraud detection. Overcoming challenges related to dataset imbalance, feature selection, and model evaluation has resulted in a robust solution with high precision and accuracy, showcasing the potential for real-world implementation in securing financial transactions.
