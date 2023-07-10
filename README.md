# Machine-learning project
The main goal of this project is to apply machine learning techniques to detect and classify bird calls in audio recordings.

It consists of 3 parts:

# 1. Data Exploration Phase: Performing initial explorative analysis on the collected annotations, recordings and audio features.
- This part mainly consisted of making conclusions from data such as seeing the class label distribution and looking at the annotator agreements
- Also taking an in depth look at the various features of each species and how they correspond to the respective labels
  
# 2. Classification Phase: Training, tuning and comparing different classification algorithms on the data.
- Performing 4 different algorithms for supervised classification of data: Random Forest, Support Vector Classification, Multi-layer Perceptron Classifier and Gaussian Naive Bayes
- The accuracy and F1 score for each of the algorithms is shown as well as for different parameters of each algorithm
- Naturally, before performing classification, standardization and dimensionality reduction techniques were performed on the data
  
# 3. Challenge Phase: Get the highest score possible on the additional unannotated bird recordings and audio features that haven't been seen before.
- Similar to the task before, but this time it was the algorithms were performed on a new test set
- The "score" was calculated by how many correct or incorrect classifications the algorithm predicted

