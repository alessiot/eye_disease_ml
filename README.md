# Eye Disease Detection with Transfer Learning

Author: Alessio Tamburro

Date: 05/28/2021

Status: Complete.

Objective:
Automated pathology detection for medical images in a realistic setup, i.e. each image may have multiple pathologies/disorders, and explain the pathology sites in  image data. We assure we work with specialists for diabetic retinopathy and glaucoma and we are interested in a predictive learning model along with feature explanability and self-learning for diabetic retinopathy and glaucoma vs. normal images.

data: from a private Kaggle contest https://www.kaggle.com/c/vietai-advance-course-retinal-disease-detection/overview

The project is organized as follows:
1. build a classification model for diabetic retinopathy and glaucoma vs normal images;
2. visualize the heatmap/saliency/features to demonstrate what regions of interest contribute to diabetic retinopathy and glaucoma, respectively;
3. using unlabelled data, augment the training data (semi-supervised learning) and report the variation in classification performance on test data set (where labels are available).

Examples of retinopathy images, their classifiaction and explanation.

https://user-images.githubusercontent.com/6719946/117159918-afb88980-ad8e-11eb-9dff-e47503b8f310.mov

Examples of glaucoma images, their classification and explanation.

https://user-images.githubusercontent.com/6719946/117159993-c1019600-ad8e-11eb-8a21-755a46b919d0.mov

