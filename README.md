# Facial_recognition_UCL
UCL machine learning assignment which involves facial recognistion 


This project aims to develop a benchmark performance measure for state of the art mahcine learning models such as SUpport vector machines and multi layer perceptons. A most 
methodologies are based on contrived image datasets, this approach uses the CelebA dataset and the cartoon dataset to create a benchmark.

The A1 file relates to the implelentation of Support vector machines here thumbnail face images are reshaped to be propagated through the classifier. It introduces a methodlogy
to optimize the hyperparameters such as kernel, gamma and regulrization parameter. This uses the Dlib library face detector for extracting face region to be reshaped into a vector 
for SVM classification. This is a binary prolem where the gender of a person is being classified based on the face images. 

The A2 file relates to the implementation of a support vector mahcine to detect emotion in a face. This uses the Dlib libray's face detector as well as the shape predictor 
to extract land mark facial regions. This is then used to be propagated though a SVM 

the B2 file implements a Multi layer perceptron for face shape prediction in a multiclass problem. This uses the same approach as in A2, howeevr, it only extracts points situated
on the outline of a a face.

