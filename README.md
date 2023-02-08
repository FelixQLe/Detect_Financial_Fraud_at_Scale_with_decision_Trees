## Detecting Financial Fraud at Scale With Decision Trees
### - Intructions on this Repo

1. Heap size error
- run this command line before run jupyter notebook on command line:

export PYSPARK_SUBMIT_ARGS=' --driver-memory 30g --driver-cores 6 --executor-memory 30g --executor-cores 6 pyspark-shell'

2. ERROR PythonRunner: Python worker exited unexpectedly (crashed) java.net.SocketException: Connection reset

- Try to run several times

### TECH STACK: MLflow, Pyspark, Jupyter, SQL

Training a machine learning model to detect fraudulent behavior involves teaching the model to identify patterns in the data that are indicative of fraud. This is done by feeding the model a large dataset of examples, where some of the examples are labeled as "fraud" and some are labeled as "not fraud." The model then uses this training data to learn the relationship between the input data and the output labels.

Training a supervised machine learning model to detect financial fraud can be challenging due to the low number of confirmed examples of fraudulent behavior. This is because financial fraud is a rare occurrence and is often difficult to detect. The limited number of examples makes it challenging for the machine learning model to learn the relationship between the input data and the output label (fraud or not fraud). If the training data is imbalanced, meaning that there are very few examples of fraud compared to the number of non-fraud examples, the model may have a tendency to classify everything as non-fraud, leading to poor performance in detecting fraud.

To overcome this challenge, various techniques can be used to balance the training data, such as oversampling the rare class (fraud) or using synthetic data generation methods. Additionally, various feature engineering techniques can be used to create new and more informative features from the existing data to improve the performance of the model.

![Fraud_not_Fraud_each_type_transactions](https://user-images.githubusercontent.com/93171100/217422354-6c7bd4ab-bf6f-48b1-b534-4f745b0fe9e5.png)


Copyright: This is from Big Book of Machine Learning Use Cases - 2nd Edition. I follow the instruction in this book with my modification, because I can not access to databrick. I use the PySpark instead to load data using Spark SQL
