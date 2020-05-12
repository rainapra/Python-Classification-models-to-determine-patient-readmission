# Python-Classification-techniques

This application will provide general idea of patient’s medical necessity based on diabetic prescription and number of times patient is re-admitted in hospital. Since, there has always been shortage of resources in medical industry whether it is hospital bed, medicines and other equipment due to large number of patients, so it is always advisable to keep the tab of patients that might use the resources in future. Our model will provide the predictions in terms of whether patient will be prescribed diabetic medication or not can really help the doctors and medical staff to keep the proper tab of patient’s health and avoid diabetic condition. This model will also determine if patient needs to be readmitted in hospital based on clinical history, medication and other factors which can help the medical staff to properly maintain and utilize medical resources as per the necessity and availability.

The dataset represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It is sourced from UCI Machine Learning Repository and has been prepared to analyze factors related to readmission as well as other outcomes pertaining to patients with diabetes. (http://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008). 
The data contains more than 1,00,000 instances and 50 attributes. The dataset is multivariate in terms of its characteristics, whereas the attributes are numerical and nominal. 

Following are some of the tasks that I am going to perform in our data model:
1.	We will use binary classification technique to determine whether the patient is given diabetic medication or not, since this label is classified into Yes or No. We will use Random Forest classifier for the above classification technique as it is the best algorithm for working with dataset having large number of attributes and it handles unbalanced data in a better way.
 
2.	The number of readmission times are categorized into three classes as no re-admission, less than 30 days and more than 30 days. Thus, we will use various multi classification techniques such as K means clustering and Random Forest classifier to determine whether the patient is re-admitted or not as they are best algorithms for working with large number of attributes and can handle unbalanced data in a better way.

Following are some steps in evaluating above model:
1)	The proposed dataset has some noisy and missing data which will be treated with proper preprocessing techniques like missing value imputation, normalization methods or standardization methods.

2)	 As there are large number of instances (approximately 0.1 million), hold out evaluation will be used to obtain the training and test dataset. We will split the data into 80-20 ratio i.e training set (80%) and test set (20%) and will start building the model using training data.

3)	We will build different models and evaluate them using accuracy score or confusion matrix to get the best working algorithm. 

