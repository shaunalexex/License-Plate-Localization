# License-Plate-Localization

Pretrained VGG16 model with imagenet weights then added dense layers and l2 regularization to deal with high variation that was found


DATASET used : https://www.kaggle.com/dataturks/vehicle-number-plate-detection

localization_using_vgg16.ipynb : run file to view outcome of model

Indian_Number_plates.json : Dataset downloaded from link above

Model used : 

![](Images/model_plot.png)

Model Loss : 

![](Images/loss.png)

Model Accuracy : 

![](Images/accuracy.png)

Results on Test Set

![](Images/1.png)

![](Images/2.png)

![](Images/3.png)

![](Images/4.png)

![](Images/5.png)

Conclusion : 

Model is good with localization but dataset cannot be used for prediction due to low quality of images and accuracy can still be increased with larger dataset 
