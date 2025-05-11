# Credit-Card-Fraud-Detection



This project explored credit card fraud detection using a Logistic Regression model, carefully following provided instructions. To build the model, I first preprocessed and normalized the transaction data using StandardScaler and removed duplicate entries. Recognizing the challenge of class imbalance, I employed SMOTE (Synthetic Minority Over-sampling Technique) to oversample the minority class (fraudulent transactions). The dataset was then split into training and testing sets using train_test_split, ensuring a robust evaluation of the model's performance.

Following the guidelines, I trained a Logistic Regression model and evaluated its performance using key metrics like accuracy, precision, recall, and F1-score. While the model achieved a high overall accuracy of approximately 97%, it's crucial to acknowledge the limitations posed by the imbalanced dataset. The significantly higher number of legitimate transactions compared to fraudulent ones can inflate accuracy as a metric, making it an unreliable indicator of performance in this context.

A deeper analysis reveals that while the model achieves a high precision of 0.51, indicating a relatively low rate of false positives, its recall of 0.95 highlights its ability to capture a high percentage of actual fraudulent transactions. This means that the model correctly identifies approximately 95% of the fraudulent transactions. However, the relatively lower precision suggests that there might be instances where legitimate transactions are misclassified as fraudulent.

The F1-score of 0.96 provides a balanced perspective, reflecting a moderate performance in both precision and recall. While not ideal, it suggests a reasonable starting point for a credit card fraud detection model, especially considering the inherent challenges of the dataset.

Despite these limitations, the initial results hold promise. Addressing the class imbalance by incorporating more fraudulent data during training could significantly improve the model's ability to accurately identify fraudulent activities. Further exploration of other performance metrics and potential model adjustments, such as fine-tuning hyperparameters or experimenting with different algorithms, is warranted to enhance its effectiveness in real-world scenarios. By adhering to the provided instructions and incorporating key elements like data preprocessing, class imbalance handling, and thorough evaluation, this project demonstrates the potential of machine learning in credit card fraud detection. With continued refinement and evaluation, such models can play a significant role in protecting against financial fraud.

This project built a fraud detection model, followed instructions, handled imbalance, and showed machine learning's potential despite limitations.



.csv file too big, here is the link for my dataset:
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
