# Project_Dogs_vs_Cats
Keras is used in this project to build CNN or reuse pretrained networks. Using a pretrained network normally consists of feature extraction and Finetuning.

## Data Set Exploration
Training set image size.
![CAT_45](figures/Training_set_image_size.png)
Possible abnormal values for cat images in training set.
![cat_abnormal_values](figures/cat_top=30_.png)
Possible abnormal values for dog images in training set.
![dog_abnormal_values](figures/dog_top=30.png)

## Basic Model
![basic_model_acc](Curve/basic_model_acc.png)
![basic_model_loss](Curve/basic_model_loss.png)


## Pre-trained Model Finetuning
### VGG16
![VGG16_acc](Curve/VGG16_acc.png)
![VGG16_loss](Curve/VGG16_loss.png)

### GoogLeNet (InceptionV3)
![InceptionV3_acc](Curve/InceptionV3_acc.png)
![InceptionV3_loss](Curve/InceptionV3_loss.png)

### ResNet50
![ResNet50_acc](Curve/ResNet50_acc.png)
![ResNet50_loss](Curve/ResNet50_loss.png)

### Xception
![Xception_acc](Curve/Xception_acc.png)
![Xception_loss](Curve/Xception_loss.png)

## Feature Integration
![model_merge](figures/model_merge.png)
![Feature_integration_acc](Curve/Feature_integration_acc.png)
![Feature_integration_loss](Curve/Feature_integration_loss.png)

## Visualizations
![CAT_45](figures/45.jpg)
![CAT_45_CAM](figures/45_CAM.png)
![CAT_45_cam](figures/45_cam.jpg)


## Report
Click here to view the Chinese version report [(PDF)](https://github.com/ViolinLee/Project_Dogs_vs_Cats/blob/master/Report_dogs_vs_cats.pdf).