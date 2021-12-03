Quality Assurance Photo Booth

This project was developed as a part of the Capstone Project (DAEN690) by a team of 5 Data Analytics Engineering - Graduate Students of George Mason University in association with Aeronautical Systems Incorporated. The primary objective of the model is developing a Deep Learning Model to classify the images of products taken by a photo booth into damaged or undamaged class. The development of the project is divided in various phases such as the following:

1. Data Collection: In the Data Collection phase, we acquired 3036 images from the Aeronautical Systems Incorporated. 

2. Data Cleanup: Manually went therough all the images in the datset and named them according to their class (i.e) Damaged/Undamaged.

3. Data Preprocessing: All the images have been scaled down to 224X224 pixels and the training dataset was aritficially multiplied using ImageDataGenerator function or Image Augmentation Technique.

4. Data Modeling: In the Modeling phase, we used a pretrained models such as RESNET50 and VGG16 to build binary and tertiary classifiers along with the traditional Convolutional Neural Network model from the basics. However, the VGG16 model has perfomed well on our dataset as it gave better accuracy when compared to the other two models. 

5. Visualizations: Accuracy Plot and Loss Plot have been generated against number of epochs executed to show the inmprovement in the performance of the model.

6. Grad-CAM Mapping: In the Visualisations phase, we used Grad-CAM and guided Grad-CAM for visualising the features used by model for classification. We also implemented Grad-CAM on the misclassified images to find out the reason for misclassification.

Model Deployment:

In order to run the model on local machine, use the compatible version of GoogleColab Pro+.

Future Work:

1. Accuracy can be improved by training the model with more and more amount of data per class. 
2. Variety of products in the images can also be increased so that the model can be trained diversely.
3. Advanced computational resources can help save some run time.
4. Misclassification rate can be decrease with better training of the model.

Team:

1. Hemanth Ghattamaneni  (Product Owner)(https://www.linkedin.com/in/hemanth-ghattamaneni-46a58b126/)
2. Sri Manjusha Yarlagadda (Scrum Master)(https://www.linkedin.com/in/srimanjusha/)
3. Surya Teja Kandhipati (Developer)(https://www.linkedin.com/in/surya-teja-kandhipati-b72012157/)
4. Bharadwaj Gadiraju  (Developer)(https://www.linkedin.com/in/bharadwaj-gadiraju-096a8311a/)
5. Saitejaswi Bellapukonda (Developer)(https://www.linkedin.com/in/saitejaswi-bellapukonda-b66618a5/)
