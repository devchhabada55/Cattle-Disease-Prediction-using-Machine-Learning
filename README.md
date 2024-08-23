### Hi! Welcome to Lumpy Skin Disease Detection in Cattle using Machine Learning : 

**Abstract :**
Lumpy Skin Disease is a viral disease that significantly impacts cattle, causing severe economic losses due to decreased milk production, loss of condition, and hide damage. The disease spreads rapidly through direct contact with infected animals or vectors such as mosquitoes and flies. This project leverages machine learning, specifically CNN and Random Forest models, to develop a predictive system that can assist veterinarians and farmers in detecting the disease early, enabling timely intervention and minimizing its spread.

**Introduction :**
Lumpy Skin Disease is a viral disease that significantly impacts cattle, causing severe economic losses due to decreased milk production, loss of condition, and hide damage. The disease spreads rapidly through direct contact with infected animals or vectors such as mosquitoes and flies. This project leverages machine learning, specifically CNN and Random Forest models, to develop a predictive system that can assist veterinarians and farmers in detecting the disease early, enabling timely intervention and minimizing its spread.

**Dataset:**
The dataset used in this project contains various features related to cattle health, including physical symptoms, environmental conditions, and possibly other diagnostic data. Each record in the dataset is labeled with whether the cattle exhibit signs of Lumpy Skin Disease (positive or negative).

**Model Selection :**
Two models are employed in this project for predicting the presence of LSD:

**System Architecture:**

![Screenshot 2024-08-23 114449](https://github.com/user-attachments/assets/6a8e7789-66ed-4fe5-9593-11940de6b63f)


**Convolutional Neural Network (CNN):**

CNNs are particularly effective for image-based data but can be adapted for structured data by treating features as channels or applying other transformation techniques.
In this project, CNNs are used to capture complex patterns and relationships within the data that may be indicative of LSD.
Random Forest:

A robust ensemble method that creates a 'forest' of decision trees and outputs the mode of the classes.
Random Forest is used here for its ability to handle imbalanced datasets and its effectiveness in feature selection and importance.
Training and Evaluation
The selected models are trained on the training set and evaluated on the test set using various metrics:

Accuracy: The percentage of correctly predicted instances.
Precision: The ratio of true positive predictions to the total positive predictions.
Recall: The ratio of true positive predictions to the total actual positives.
F1-Score: The harmonic mean of precision and recall, providing a balance between the two.
Results
The performance of the models is presented through:

Confusion Matrix: Visualizing true positives, true negatives, false positives, and false negatives.
ROC Curve: Analyzing the trade-off between the true positive rate and false positive rate.
Model Interpretability: Discussing feature importance (in the case of Random Forest) and the impact of different features on the model's predictions.

**Conclusion :**
The project demonstrates the application of CNN and Random Forest models in predicting the presence of Lumpy Skin Disease in cattle. The developed models provide valuable tools for early detection, which is critical in managing and controlling the spread of this disease.

**Future Work :** 
Potential areas for improvement and further research include:

Collecting more data to improve model accuracy.
Implementing advanced deep learning techniques for better feature extraction and prediction.
Developing a real-time detection system integrated with IoT devices for monitoring cattle health.
