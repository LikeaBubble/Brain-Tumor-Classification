# Brain Tumor Classification  
## Problem Description
* Todays which the hand of AI is visible in any field you can think about, it's also important in healthcare and medical perposes.
* In my opinion (as a learner in CV field) CV in healthcare is not reliable yet, Even the models are highly accurate, we cannot still trust them when human lives are at stake.
* But instead of rely on themselves we can use them in specific processes to help us in making decisions more reliable in less time.
* In this project I want to use MRI images to train a model which predicts the probability of existence of 3 types of brain tomur or non of them.
## Dataset  
* Kaggle Brain Tumor MRI Dataset contains about 1300 brain MRI images for each of following classes (and also 300 images for each class in test folder):
  1. No tumor  
  2. Glioma tumor  
  3. Meningioma tumor  
  4. Pituitary tumor
* As you know images are gray scale and have 1 channel
* Resolution of images are 512x512 
* Link: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
* Some samples from trainset:
  <img width="777" height="777" alt="output1" src="https://github.com/user-attachments/assets/97677fbd-6ab6-44da-9dc1-d0e04655d901" />

## Solution & Results
* Training details are as following:
  1. Pre-trained resnet50
  2. Image size : 244x244
  3. Augmentation (Horizontal & Random flip)
* After 5 epochs, results are as following:
  - Accuracy on Validation set: 92%
  - Accuracy on unseen data: 89%  
  - Predictions on testset:  
    <img width="777" height="777" alt="output" src="https://github.com/user-attachments/assets/07192dfc-817d-4bac-87df-bbe9ee19c27d" />

