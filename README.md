# AMD_classification
Decision Support System for Age-Related Macular Degeneration Using Convolutional Neural Networks


Overview


Age-related Macular Degeneration (AMD) is one of the leading causes of irreversible vision loss worldwide. Early detection of AMD is crucial for preventing disease progression and supporting timely treatment.


This study proposes a decision support system for the classification of AMD and normal retinal fundus images using Convolutional Neural Networks (CNNs).



Research Objective


The main objective of this work was to develop an automated system capable of distinguishing between AMD and healthy retinal fundus images to assist ophthalmologists in early diagnosis and screening.



Materials and Methods


Dataset


Two datasets were used in this study:






Local dataset (Iran University of Medical Sciences)




3195 retinal fundus images


2070 AMD suspect images


1125 healthy images


Captured using TOPCON fundus camera (1451×1451 resolution)








STARE dataset




201 retinal images


36 healthy images


47 AMD images








To improve model performance, data augmentation techniques were applied, including:




Horizontal flipping


Random cropping


Data transformation and combination methods





Deep Learning Model


A Convolutional Neural Network (CNN) was used for image classification.


The network architecture included:




Convolutional layers for feature extraction


ReLU activation functions


Pooling layers for dimensionality reduction


Fully connected layers for classification


Softmax output layer




The model was based on the LeNet architecture and trained using pre-processing and fine-tuning techniques.



Training Strategy




Images were resized to 32×32×3 for input to the network


Training and testing split was applied


The model was trained for 15 epochs


MATLAB MatConvNet toolbox was used for implementation


Training and validation errors were monitored during learning





Results


The proposed CNN-based system achieved strong classification performance:




Local dataset accuracy: 0.95


STARE dataset accuracy: 0.81




The results demonstrate that deep learning can effectively support automated detection of AMD from retinal fundus images.



Discussion


The study shows that manual feature extraction methods used in traditional machine learning approaches are time-consuming and dependent on expert knowledge. In contrast, CNNs enable automatic feature extraction, improving both accuracy and efficiency.


The system demonstrated high potential for large-scale screening and fast diagnosis of AMD.



Conclusion


This research presents a CNN-based decision support system for AMD detection using retinal fundus images. The proposed method improves diagnostic efficiency and can assist ophthalmologists in early detection of retinal diseases.


Future work includes improving generalization across datasets and enhancing model robustness for clinical applications.



Technologies Used




MATLAB (MatConvNet)


Convolutional Neural Networks (LeNet architecture)


Image augmentation techniques


Medical retinal fundus imaging datasets





Clinical Significance


Early detection of AMD is essential for preventing vision loss. This system provides a step toward automated and reliable screening tools that can assist clinicians in large-scale retinal image analysis.



Citation


Langarizadeh M., Maghsoudi B., Nilforushan N. (2017).

Decision Support System for Age-Related Macular Degeneration Using Convolutional Neural Networks.

Iran Journal of Medical Physics.

