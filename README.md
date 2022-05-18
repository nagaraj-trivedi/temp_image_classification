# Melanoma Detection based on multiclass classification model using custom convolution neural network in tensorflow
> This project is about building a CNN based model in TensorFlow which can accurately detect melanoma


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
> The purpose of this project is to build a custom CNN model in tensorflow to 
> 
> 1. Build a basic model with the given initial size of the data and evaluate training as well as validation accuracy and loss
> 2. Plot the graph and observe whether it is overfitting or underfitting
> 3. Choose an appropriate data agumentation, build the model and obverse the training as well as validation accuracy and loss
> 4. Introduce drop out, build the model and observe the training as well as validation accuracy and loss
> 5. Plot the graph, observe the distribution of images and each class and find out which class has got lesser number of images and which classes have got higher proportionate of distribution of images
> 6. Perform data augmentation with the augmentor library and class rebalance with 500 images in every class through augmentation
> 7. Rebuild the model with augmented data size and observe the train, validation accurach and loss
> 8. Evaluate all these models and choose a right model for prediction on the test images
> 9. Perform predictions on the test images, observe the accuracy and provide a conclusion

> 1.With given initial size of the data set perform the following
   -  Find the training and validation accuracy aswell as the loss
   -  Check whether it underfits/overfits
   -  Check is there a class imbalance

> 2.Rebuild the model with manual data augmentaion and perform the following
   -  Find the training and validation accuracy aswell as the loss
   -  Check whether it underfits/overfits
   -  Check is there a class imbalance
> 3.Rebuild the model with manual data augmentaion and perform the following
   -  Find the training and validation accuracy aswell as the loss
   -  Check whether it underfits/overfits
   -  Check is there a class imbalance
> 5. Perform data augmentation with augmentation library, train the model and observe the parameters in step 1 to 3
> 6. Write the final conclusion
- The background of this project is to build a model with high accuaracy and lesser loss which can be used for melanoma detection
- It solves the business problem of health care industry particurly cancer and the dermatology.
- What is the dataset that is being used?
- Data set from International Skin Imaging Collaboration (ISIC)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis with Model 1
> With a total of 2239 images in the train data set the train accuracy was 0.90 and the validataion accuracy was 0.52 The model was overfitting
- Conclusion 2 from the analysis with Model 2
> Using manual data augmentation technique and drop out the train accuracy was 0.71 and validation accuracy was 0.52
> There was no increse in the train accuracy compared to Model 1. The only improvement is that validation loss was lesser compared to Model 1. But still the model overfitts
- Conclusion 3 from the analysis with Model 3
- Model 3 was built with data augmentation about 500 images in each of the classes
- The train accuracy was greater than 0.9 and the validataion accuracy was greater than 0.8
- Both train and validation loss got reduced significantly
- The final model was free from overfitting and the class rebalance really helped to overcome the overfitting
- Conclusion 4 from the analysis with Model 3 using augmentor library there were 6739 images

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- libraries from tensorflow, pandas, numpy, matplotlib, pathlib, os, io
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the upgrad learning coarse on CNN as part of the Deep Learning
- References
> https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6231861/
> 
- This project was based on [this tutorial](https://learn.upgrad.com/course/1992?courseId=12362).


## Contact
Created by [@nagaraj-trivedi] - feel free to contact me!
<!-- This project is open source and available under the [... License](). -->
