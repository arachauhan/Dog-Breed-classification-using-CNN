## Dog Breed classification using CNN
 
 ### Introduction
 
 This project is part of Data Science Nan Degree from Udacity
 
 ### Motivation
 This project aims at identifying dog images in to 133 different dog's breed using Artificial Intelligence and Deep Learning Techniques applying Convolutional Neural Networks (CNNs). We are going to build a pipeline to process real-world, user-supplied images and given an image of a dog, algorithm will identify an estimate of the canine's breed. If supplied an image of a human, the algorithm whether the image contains a human, dog, or neither -
- if a dog is detected in the image, return the predicted breed.
- if a human is detected in the image, return the resembling dog breed.
- if neither is detected in the image, provide output that indicates an error.

This project has below steps:

- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dogs
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 6: Write your Algorithm
- Step 7: Test Your Algorithm

## Libraries used
- tensorflow
- keras
- numpy
- matplotlib
- cv2
- Sklearn

## Conclusion
The model performed at 79% accuracy that is satisfcatory and testing upon 7 images it is showing right results however accuracy can be improved by follwing below points:
- Increase training and testing data
- Image data augmentation to increase the number of training images.
- Improve the network design by doing more experimentation and adding few more layers and trying different type CNN models like Inception, Xception Accuracy can be further optimised by ensembling results of different CNN models.
- Hyperparameter tuning of the CNN models
- Use Cross validation while training of the model

## Blog post
[Link to the blog post on Medium.](https://medium.com/@arachauhan/dog-breed-classification-using-convolutional-neural-networks-cnn-b17423366f4d)


## Reference
Project dataset is provided by Udacity and this project is  part of [Data Scientist Nanodegree.](https://www.udacity.com/course/data-scientist-nanodegree--nd025)
