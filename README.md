
## Kaggle Airbus Ship Detection Challenge

This project is for Kaggle competiton [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection).

This is an implementation of [Mask R-CNN](https://arxiv.org/abs/1703.06870) on Python 3, Keras, and TensorFlow. The model generates bounding boxes and 
segmentation masks for each instance of an object in the image. 

![infer_example](assets/ship.png)

## File strcture

AirBus  

1. PY -> Train Mask_RCNN.ipynb (Create dataset, config and train model)                      
2. assets                    

## Resources

The project was based on [Object Detection Model with Keras](https://machinelearningmastery.com/how-to-train-an-object-detection-model-with-keras/).

As an object detection mode [Mask RCNN](https://github.com/akTwelve/Mask_RCNN.git) was used. 
