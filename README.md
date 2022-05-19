# Brain-Tumor-Detection-and-Classification
A Comparative Study of Machine Learning and Deep Learning Algorithms for Brain Tumor Detection and Classification

Brain tumor is considered as one of the aggressive diseases, among children and adults. Brain tumors account for 85 to 90 percent of all primary Central Nervous System tumors. Every year, around 11,700 people are diagnosed with a brain tumor. The 5-year survival rate for people with a cancerous brain or CNS tumor is approximately 34 percent for men and 36 percent for women. BrainTumors are classiﬁed as: Benign Tumor, Malignant Tumor, Pituitary Tumor, etc. Proper treatment planning and accurate diagnostics should be implemented to improve life expectancy of the patients. The best technique to detect brain tumors is Magnetic Resonance Imaging (MRI). Huge amounts of data images are generated through the scans. These images are examined by the radiologist. Manual examination can be error prone due to the level of complexities involved in brain tumors and their properties. Application of automated classiﬁcation techniques using Machine Learning(ML) and Artiﬁcial Intelligence(AI) has consistently shown higher accuracy than manual classiﬁcation.
Hence, we propose performing detection and classiﬁcation by using various Machine Learning and Deep Learning Algorithms using Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Convolution Neural Network (CNN) and VGG-16 to compare and achieve higher accuracy. The MRI images are classiﬁed using different ‘Machine Learning and Deep Learning Models’. These models have permutations and combinations of different ‘Hyper Parameters’. The model with the highest accuracy is selected and deployed. The aim of the project is to achieve higher accuracy and reliability for real world MRI data using ML domain knowledge. Further to compare various model accuracies, suggest the best model for classification of tumor and detect the category of brain tumor in the MRI scans.


# Objective
Our aim is to develop an automated system for enhancement, segmentation and classification of brain tumors. The system can be used by neurosurgeons and healthcare specialists. The system incorporates image processing, pattern analysis, and computer vision techniques and is expected to improve the sensitivity, specificity, and efficiency of brain tumor screening. The primary goal of medical imaging projects is to extract meaningful and accurate information from these images with the least error possible. The proper combination and parameterization of the phases enables the development of adjunct tools that can help in the early diagnosis or the monitoring of the tumor  identification and locations.


# Dataset
The dataset of the proposed framework has been taken from the kaggle repository. There are four classes in the dataset which consists of 826 brain MRI images of glioma tumor, 822 images of meningioma tumor, 847 images of pituitary tumor and 395 images with no tumor. Thus, a total of 2890 images are present. 
80% of the dataset has been used for trainng where as 20% for testing purposes.


# Results and Discussion

The following parameters have been used to assess the prediction results:
Precision: It is the measure of points that are actually positive, out of all the points in a model predicted positive.
Recall: It is the measure of points predicted to be positive out of those which are actually positive in a model.
F1 Score: The harmonic mean between Precision and Recall is coined as F1 score.
Accuracy: It is the number of correctly classified points out of the total number of points in a model.

Obtained values of precision, recall, F1 score and accuracy for classification of ML  models. Naive Bayes models are the least suited for the image classification of brain tumors. It can be seen that Random forest shows best results due to its improved generalization and  embedded ensemble learning feature.
Obtained values of precision, recall, F1 score and accuracy for classification of four DL models. The performance is highest for our proposed CNN model with an accuracy of 92% which is more than all other models trained.



# Appications
Magnetic resonance (MR) imaging and computed  tomography (CT) scans of the brain are the two most general tests to check the existence of a tumor as of now. Radiologists have to manually check and test the positioning and type of tumor based on the MRIs. This process of classifying brain tumors is both tedious and time consuming. So in order to  decrease the level of complexities involved in brain tumors and their properties, this model has been proposed. Application of automated classiﬁcation techniques using Machine Learning and Artiﬁcial Intelligence has consistently shown higher accuracy than manual classiﬁcation. Thus we propose our CNN model to classify images in order to help medical specialists in automated classification of tumors. 
