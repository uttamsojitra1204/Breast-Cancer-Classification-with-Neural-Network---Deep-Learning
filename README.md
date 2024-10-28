# Breast-Cancer-Classification-with-Neural-Network---Deep-Learning

=> This project focuses on developing a neural network model to classify breast tumors as either benign or malignant using the Wisconsin Breast Cancer dataset. With 569 samples and 30 numerical features representing tumor cell nuclei characteristics, the dataset was preprocessed, standardized, and divided into training and testing sets to ensure balanced and reliable model performance.

1. Library Import and Data Collection:
- Necessary libraries like pandas, numpy, sklearn, and tensorflow are imported.
- The breast cancer dataset is loaded using sklearn.datasets.load_breast_cancer().

2. Data Preprocessing:
- The data is checked for null values, with no null entries detected.
- Data is split into features (X) and labels (Y), followed by a train-test split.

3. Data Standardization:
- StandardScaler is applied to the feature data for normalization.

4. Neural Network Model Setup:
- A simple neural network with one hidden layer is created using Keras.
- The model is compiled using the Adam optimizer and trained for 10 epochs, achieving good accuracy on the validation set.

5. Evaluation and Visualization:
- Accuracy and loss are plotted for both training and validation sets to visualize performance.
- The model achieves high accuracy on test data, indicating it performs well on breast cancer prediction.

=> Contact Us

1. Email: uttamsojitra.ds@gmail.com

2. LinkedIn: https://www.linkedin.com/in/uttam-sojitra-6aa781236/

Feel free to reach out for any collaboration, job opportunities, or project discussions!

- Accuracy and loss are plotted for both training and validation sets to visualize performance.
- The model achieves high accuracy on test data, indicating it performs well on breast cancer prediction.

=> Conclusion
- The neural network model is highly effective for breast cancer classification, achieving a high test accuracy. This suggests the model's robustness and reliability in predicting tumor malignancy, which could be valuable in medical diagnostics, particularly as a preliminary tool to assist healthcare professionals. Further enhancements could involve hyperparameter tuning, increasing the dataset size, or experimenting with deeper architectures to improve performance further.
