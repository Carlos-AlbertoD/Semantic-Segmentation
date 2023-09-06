# Semantic-Segmentation
## AWS Semantic Segmentation Project

I used a ResNet-50 backbone to train a model to execute Semantic Segmentation on pictures from the Oxford-IIIT Pet Dataset.
Possible label values for each pixel were [1,2,3], to allow the model to establish whether a pixel belonged to the subject, the background, or a transition between the two.
Model training was done through an AWS Sagemaker Estimator.
