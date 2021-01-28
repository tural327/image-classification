# image-classification

[Project - Environment Picture classification](https://github.com/tural327/image-classification/tree/main/environment_classification)

-Define images parameters and loaded with image_dataset_from_directory

-I divided training data 0.2 for validation 0.8 training

-RGB values are [0,255] to get betweet [0.1] normalization_layer added

-After training model was overfit :
![](https://github.com/tural327/image-classification/blob/main/environment_classification/Loss%20overfit%20model.png)
![](https://github.com/tural327/image-classification/blob/main/environment_classification/Accurancy%20overfit%20model.png)

- preventing overfitting data_augmentation added for adding image various sides

-model trained again and result was : 
![](https://github.com/tural327/image-classification/blob/main/environment_classification/loss%20for%20normal%20model.png)
![](https://github.com/tural327/image-classification/blob/main/environment_classification/Accurancy%20for%20normal%20model.png)

- End of training I testing my model with testing data and result was 0.81%
