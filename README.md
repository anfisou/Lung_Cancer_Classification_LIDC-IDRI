# IACD LAB Project 1 - Lung Cancer Image Classification

Work developed for the IACD Lab course. 
The project consists of using Computerized Tomography (CT) images as input data to build one or more learning models capable of classifying new images as i.e. predicting whether there is a malignant nodule on the scan or not.

The input data is obtained from the Lung Image Database Consortium image collection (LIDC-IDRI), a public dataset of thoraci CT scans. Utilizing python open source libraries (namely pylidc and pyradiomics) we were able to extract from the scans in this dataset several features and a label which we use to train and developed various machine learning algorithms.

Our main objective is to develop an algorithm that not only generalizes well to unseen data (meaning it performs well at classifying new images) but also that tackles real world concerns regarding the use of ML models for healthcare, such as intepretability (can the medical professionals understand how the model reached a certain classification?) and expressivity (is the output of the model just a number or class or does it have context that can be critical for the decision making of medical professionals?).
The final version of the work developed is specified in the following files:

- Main.ipynb - jupyter notebook, collection of the code progress along with comments and explanations
- documentos - useful information and all the data to process
