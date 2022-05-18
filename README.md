# Melanoma Detection based on multiclass classification model using custom convolution neural network in tensorflow
> This project is about building a CNN based model in TensorFlow with highest accuracy which performs melanoma cancer prediction with highest accuracy


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
> The purpose of this project is to build a custom CNN model in tensorflow to 
> 
> 1. Build a basic model with the given initial size of the data and evaluate training as well as validation accuracy and loss
> 2. Plot the graph and observe whether it is overfitting or underfitting
> 3. Build the next model by choosing an appropriate data agumentation, and obverse the training as well as validation accuracy and loss
> 4. Introduce drop out, build the model and observe the training as well as validation accuracy and loss
> 5. Plot the graph, observe the distribution of images under each class and find out which class has got lesser number of images and which classes dominate higher proportionate of distribution of images
> 6. Perform data augmentation with the augmentor library and class rebalance with augmentation of 500 images in every class through augmentation
> 7. Rebuild the model with augmented data size and observe the train, validation accuracy and loss
> 8. Evaluate all these models to find out which model has got higher train and validation accuracy, free from overfit/underfit and choose a right model for prediction on the test images
> 9. Perform predictions on the test images
- The background of this project is to build a model with high accuaracy and lesser loss which can be used for melanoma detection
- It solves the business problem of health care industry particurly in the field of cancer and dermatology
- Data set from International Skin Imaging Collaboration (ISIC) is used for training aswell as performing prediction

## Conclusions
- Conclusion 1 from the analysis with Model 1
> With a total of 2239 images in the train data set the train accuracy was 0.90 and the validataion accuracy was 0.52 The model was overfitting
- Conclusion 2 from the analysis with Model 2
> Using manual data augmentation technique and drop out the train accuracy was 0.71 and validation accuracy was 0.52
> There was no increse in the train accuracy compared to Model 1. The only improvement seen was the validation loss was lesser compared to Model 1. But still the model overfitts
- Conclusion 3 from the analysis with Model 3
- Model 3 was built with data augmentation about 500 images in each of the classes and the total number of images from all the classes were 6739
- The train accuracy was 0.91 and the validataion accuracy was greater than 0.82
- Train loss was 0.24 and validataion loss was 0.70
- Both train and validation loss got reduced significantly
- The final model was free from overfitting and the class rebalance really helped to overcome the overfitting. This final model (Model 3) was chosen for prediction on the test data set

## Technologies Used
- tensorflow version 2.8.0
- pandas version 1.3.5
- numpy 1.21.6
- matplotlib 3.2.2

## Acknowledgements
Give credit here.
- This project was inspired by the upgrad learning coarse on CNN as part of the Deep Learning
- References
> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6231861/
> 
- This project was based on [this tutorial](https://learn.upgrad.com/course/1992?courseId=12362).
- Finally thanks to the distinguished professors from IIITB Bengaluru and other professor for teaching the basic concepts on ML and Deep Learning


## Contact
Created by [@nagaraj-trivedi] - feel free to contact me!
