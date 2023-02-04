## Detecting Financial Fraud at Scale With Decision Trees

### TECH STACK: MLflow, Pyspark, Jupyter, SQL

Training a machine learning model to detect fraudulent behavior involves teaching the model to identify patterns in the data that are indicative of fraud. This is done by feeding the model a large dataset of examples, where some of the examples are labeled as "fraud" and some are labeled as "not fraud." The model then uses this training data to learn the relationship between the input data and the output labels.

Training a supervised machine learning model to detect financial fraud can be challenging due to the low number of confirmed examples of fraudulent behavior. This is because financial fraud is a rare occurrence and is often difficult to detect. The limited number of examples makes it challenging for the machine learning model to learn the relationship between the input data and the output label (fraud or not fraud). If the training data is imbalanced, meaning that there are very few examples of fraud compared to the number of non-fraud examples, the model may have a tendency to classify everything as non-fraud, leading to poor performance in detecting fraud.

To overcome this challenge, various techniques can be used to balance the training data, such as oversampling the rare class (fraud) or using synthetic data generation methods. Additionally, various feature engineering techniques can be used to create new and more informative features from the existing data to improve the performance of the model.
