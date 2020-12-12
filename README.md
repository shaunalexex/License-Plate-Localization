# License-Plate-Localization

Pretrained VGG16 model with imagenet weights then added dense layers and l2 regularization to deal with high variance that was found


DATASET used : https://www.kaggle.com/dataturks/vehicle-number-plate-detection

localization_using_vgg16.ipynb : run file to view outcome of model

Indian_Number_plates.json : Dataset downloaded from link above

Framework used : 

Tensorflow and Keras

Model used : 

![](Images/model_plot.png)

Model Loss : 

![](Images/loss.PNG)

Model Accuracy : 

![](Images/accuracy.PNG)

Results on Test Set

![](Images/1.PNG)

![](Images/2.PNG)

![](Images/3.PNG)

![](Images/4.PNG)

![](Images/5.PNG)

Conclusion : 

Model is good with localization but dataset cannot be used for prediction due to low quality of images and accuracy can still be increased with larger dataset 
