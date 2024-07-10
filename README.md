# Big Data: Tokyo Accommodation Availability Prediction


## Introduction

This project demonstrates a data processing and machine learning pipeline. HDFS (Hadoop Distributed File System) was used as the primary storage system and Apache Spark (PySpark) for data processing. This project was developed as a continuous assignment for «Storage Solutions for Big Data» during my college studies.

The project involves:
1. Loading the dataset files to HDFS.
2. Processing these files using PySpark.
3. Storing the processed data in Apache Parquet format.
4. Loading the data from Parquet.
5. Training a machine learning model on the data.
6. Using the trained model to make predictions on new data provided by the user through interactive widgets (iwidgets), simulating a website experience.

## Features
- **HDFS Integration**: Efficiently store and manage large datasets using HDFS.
- **PySpark Processing**: Utilize the power of Apache Spark for large-scale data processing.
- **Parquet Storage**: Store processed data in the optimized Parquet format.
- **Machine Learning**: Train machine learning models on the processed data.
- **Interactive Widgets**: Allow users to input new data and get predictions from the trained model.

The dataset used for this project can be found on Kaggle: [Dataset Link](https://www.kaggle.com/datasets/lucamassaron/tokyo-airbnb-open-data-2023/)
