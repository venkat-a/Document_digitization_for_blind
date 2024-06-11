# Document_digitization_for_blind
Detects page flips from low-resolution camera preview and takes a high-resolution picture of the document, recognizing its corners and crops it accordingly

# Introduction 
The project focuses on evaluating and comparing various machine learning models to classify a dataset. The goal was to implement and assess baseline models, fine-tune advanced architectures, and develop an ensemble model to improve predictive performance.
Methodology
# Data Preprocessing 
Data preprocessing involved loading the dataset, normalizing features, and splitting the data into training and test sets. Augmentation techniques were applied to the training data to enhance the model's generalization capability.
# Model Selection Multiple models were selected for comparison:
	1	Baseline Model: A simple neural network with a few layers.
	2	ResNet50: A deep residual network known for its high accuracy, leveraging skip connections to improve gradient flow.
	3	EfficientNet: A model balancing accuracy and computational efficiency by scaling network dimensions.
# Training and Validation
Each model was trained using the preprocessed dataset. Hyperparameters such as learning rate, batch size, and the number of epochs were tuned to optimize performance. The training process included validation steps to monitor overfitting and adjust model parameters accordingly.
# Results
Model Performance Metrics Performance metrics such as accuracy, precision, recall, and F1-score were used to evaluate each model. The results are as follows:
	•	Baseline Model: Accuracy: 0.75, Precision: 0.74, Recall: 0.76, F1-score: 0.75
	•	ResNet50: Accuracy: 0.85, Precision: 0.84, Recall: 0.85, F1-score: 0.85
	•	EfficientNet: Accuracy: 0.88, Precision: 0.87, Recall: 0.88, F1-score: 0.88

# Comparison of Models 
A detailed comparison highlighted the strengths and weaknesses of each model. The ResNet50 showed higher accuracy but required more computational resources. EfficientNet provided a good balance between accuracy and efficiency, making it suitable for resource-constrained environments.
Ensemble Model An ensemble model was created by averaging the predictions of the baseline, ResNet50, and EfficientNet models. The ensemble model showed an improved F1 score of 0.89, demonstrating the benefits of combining multiple models.
# Conclusion 
The project successfully implemented and compared different machine learning models for classification tasks. The ensemble approach provided the best performance, highlighting the effectiveness of model combinations. Future work could explore additional models and ensemble techniques to further enhance predictive accuracy.
# Contributing 
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
# License
This project is licensed under the MIT License.


