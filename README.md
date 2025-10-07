Penguin Species Prediction


Problem Statement:


This project builds a machine learning model to predict the species of a penguin based on its physical attributes such as bill length, bill depth, flipper length, and body mass.
The goal is to assist researchers and ecologists in classifying penguin species in the field without requiring expert biologists for manual identification.



Approach & Evaluation:


-	Model Used: Decision Tree Classifier


-	Hyperparameters Tuned: max_depth, max_leaf_nodes


-	Train Accuracy: 100%


-	Test Accuracy: 98.05%


-	Cross-Validation Scores: [0.9855, 0.9855, 0.9855, 0.9706, 0.9411]


-	Mean CV Score: 97.36%


-	Evaluation Metrics: Accuracy, Confusion Matrix, Cross-Validation, Classification Report



Even though training accuracy is 100%, the test and cross-validation accuracies are consistently high and close indicating a well-balanced Decision Tree model.





Dataset & Tools Used:


	Dataset: Palmer Penguins dataset (penguins.csv) containing:


-  bill_length_mm
  

-  bill_depth_mm

  
-	flipper_length_mm


-	body_mass_g


-	island


-	sex


-	species (target variable)




	Tools & Libraries:


-	Python

  
-	Pandas, NumPy

  
-	Matplotlib, Seaborn (visualization)

  
-	Scikit-learn (modeling & evaluation)


Conclusion:


The Decision Tree model predicts penguin species with high accuracy (98.05% on the test set) and generalizes well, as shown by cross-validation scores. It can assist researchers in classifying penguins quickly and accurately. Future improvements could include using ensemble models or deploying the model for field use.

