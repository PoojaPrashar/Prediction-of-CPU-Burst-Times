# Prediction-of-CPU-Burst-Times
Developed a novel technique of estimating CPU burst-times using machine learning algorithms. Analyzed K-Nearest Neighbor and Simple Vector Machine (SVM) implementations using Pandas, Matplotlib, Weka and Google Cloud.

Prediction of CPU burst times using Machine Learning Algorithms

The implementation of CPU-Scheduling algorithms such as Shortest-Job-First (SJF) and Shortest Remaining Time First (SRTF) require knowing the length of the CPU-bursts for processes in the ready queue. Dataset used is "GWA-T-4 Auver Grid" which has more than 4 lakh jobs. http://gwa.ewi.tudelft.nl/datasets/gwa-t-4-auvergrid

These steps are summarized as following:

Preparing/creating the dataset: The dataset is analysed and the columns having missing values and those having a zero correlation coefficient are dropped and the final dataset is created.

Attributes filtering/selecting: Feature selection techniques were applied to select the most significant attributes by applying feature selection technique. And after that normalization is applied on the dataset.

Generating the model: In this step ML techniques KNN and Decision tree is applied on the dataset.

Evaluating the model: In this step, the testing dataset was used to evaluate the generated model, in the previous step. The performance of the generated model was then evaluated in terms of Correlation Coefficient (CC) and R2 Score(R2_Score).

Predicting the CPU burst time of the test data.


