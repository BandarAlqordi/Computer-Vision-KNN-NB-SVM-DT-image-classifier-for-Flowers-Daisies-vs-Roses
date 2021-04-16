# Computer-Vision-KNN-NB-SVM-DT-image-classifier-for-Flowers-Daisies-vs-Roses
Introduction
	This report will investigate the accuracy of 4 image classifiers KNN, Naïve Bayes, Support Vector Machine (SVM), Decision Tree with a dataset consisting of 1273 images of flowers split into two labels daisy or rose. 
	 
Figure 1 25 Images from the dataset with their labels
![25 Images from the dataset with their labels Results](https://user-images.githubusercontent.com/76955490/115043288-06901900-9edd-11eb-9d71-6f22dd3c929d.jpg)

Results

 
K-nearest neighbors Classifier
Table 1 Classification report for flower dataset using KNN
	precision	recall	f1-score	support
daisy	0.73	0.61	0.67	149
rose	0.70	0.81	0.71	170
				
accuracy			0.71	319
macro avg	0.72	0.71	0.71	319
weighted avg	0.72	0.71	0.71	319

Naïve Bayes Classifier

Table 2 Classification report for flower dataset using Naïve Bayes
	precision	recall	f1-score	support
daisy	0.68	0.77	0.73	149
rose	0.77	0.69	0.73	170
				
accuracy			0.73	319
macro avg	0.73	0.73	0.73	319
weighted avg	0.73	0.73	0.73	319

CLASSIFIER	KNN	Naïve Bayes	SVM	Decision Tree
ACCURACY	0.71	0.73	0.73	0.63


Support Vector Machine (SVM)
Table 3 Classification report for flower dataset using Support Vector Machine (SVM)
	precision	recall	f1-score	support
daisy	0.69	0.78	0.73	149
rose	0.78	0.69	0.74	170
				
accuracy			0.73	319
macro avg	0.74	0.74	0.73	319
weighted avg	0.74	0.73	0.73	319

Decision Tree Classifier

Table 4 Classification report for flower dataset using Decision Tree
	precision	recall	f1-score	support
daisy	0.60	0.62	0.61	149
rose	0.66	0.63	0.64	170
				
accuracy			0.63	319
macro avg	0.63	0.63	0.63	319
weighted avg	0.63	0.63	0.63	319
 
Conclusion
	Although Naïve Bayes and SVM classifiers have the same accuracy of 73% the precision, recall, f1-score is slightly higher in the SVM classifier making it the better classifier for this case.

