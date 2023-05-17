# Phishing Site Detection using Machine Learning
Welcome to the repository for the Phishing Site Detection project! This project focuses on detecting phishing websites using machine learning techniques. A custom random forest algorithm is employed as it exhibits the highest accuracy among various algorithms tested.

## Description
Phishing attacks pose a significant threat to users' online security. This project aims to develop a machine learning model capable of accurately identifying phishing websites. The process involves the following steps:

_**Dataset**_: A list of URLs is taken as input for training and testing the model. The dataset contains a mixture of legitimate and phishing URLs.<br>

_**Feature Extraction**_: The project utilizes a feature extraction technique specifically designed for phishing detection from URLs. This process extracts relevant features that aid in differentiating between legitimate and phishing URLs.<br> 

_**Splitting and Merging**_: The extracted URLs are divided into legitimate and phishing URLs. The datasets are then merged and shuffled to create a balanced dataset.<br>

_**Training and Testing**_: Various machine learning algorithms are applied to the dataset for training and testing. The performance of each algorithm is evaluated using accuracy validation.<br>

_**Random Forest Algorithm**_: Among the tested algorithms, the custom random forest algorithm demonstrates the highest accuracy. It is selected as the final model for phishing site detection.<br>

_**Model Persistence**_: The trained random forest model is saved as a .sav file, ensuring easy accessibility and reusability.<br>

_**Deployment**_: The model is deployed on a basic website using Django framework, enabling users to input URLs for phishing detection.<br>


## Repository Structure
The repository consists of the following files and directories:

_**csv and txt**_: Contains the dataset of URLs used for training and testing.

_**Phishing website features**_: Documentation and code related to the feature extraction technique.

_**Comparison between Accuracies of different ML models**_: Code for splitting, merging, training, and evaluating various machine learning algorithms.

_**Custom_rf_classifiers.sav**_: The custom random forest model saved as a .sav file.
