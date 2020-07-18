# Pilot task

## Goal
* Comparing **mxnet-gluon** backend on **resnet18_v1, resnet18_v2** and **resnet34_v1** architecture using the given dataset.

## Steps
* Installing Monk.
* Loading the dataset.
* Importing **mxnet-gluon**.
* Training a transfer learning model using **resnet18_v1** architecture.
* Training a transfer learning model using **resnet18_v2** architecture.
* Training a transfer learning model using **resnet34_v1** architecture.
* Comparing the above models using the **comparison** class of Monk for training accuracy, validation accuracy, training loss, validation loss, time taken in training and GPU usage.

## About the [dataset](https://drive.google.com/file/d/0BxDIywue_VABY1dRcFVvZ3BodnM/view?usp=sharing)
* The dataset contains a total of 145436 images divided into seven class namely, 'Exterior', 'bedroom', 'kitchen', 'living_room', 'Interior', 'bathroom', 'dining_room'.
* Images in each class:
  * Images in Exterior folder 24869
  * Images in bedroom folder 24123
  * Images in kitchen folder 24234
  * Images in living_room folder 24210
  * Images in Interior folder 19000
  * Images in bathroom folder 9501
  * Images in dining_room folder 19500
* Sample images of each class:

![Exterior](https://github.com/rohit0906/monk_task/blob/master/images/exterior.jpeg) ![Interior](https://github.com/rohit0906/monk_task/blob/master/images/interior.jpeg) ![Living room](https://github.com/rohit0906/monk_task/blob/master/images/living.jpeg) ![dining](https://github.com/rohit0906/monk_task/blob/master/images/dining%20room.jpeg) ![bedroom](https://github.com/rohit0906/monk_task/blob/master/images/bedroom.jpeg) ![bathroom](https://github.com/rohit0906/monk_task/blob/master/images/bathroom.jpeg) ![kitchen](https://github.com/rohit0906/monk_task/blob/master/images/kitchen.jpeg) 






## About the framework and architecture used
* The framework used for the task is mxnxt-gloun.
* Using **resnet18_v1**, **resnet18_v2** and **resnet34_v1** architecture for transfer learning.

## Results
Following result graph were obtained:
![Training Accuracy](https://github.com/rohit0906/monk_task/blob/master/images/training_accuracy.png) ![Training Loss](https://github.com/rohit0906/monk_task/blob/master/images/training_loss.png)
![Validation Accuracy](https://github.com/rohit0906/monk_task/blob/master/images/val_accuracy.png)
![Validation Loss](https://github.com/rohit0906/monk_task/blob/master/images/val_loss.png)
![Tike Taken](https://github.com/rohit0906/monk_task/blob/master/images/time_taken.png)
![MAX GPU Usage](https://github.com/rohit0906/monk_task/blob/master/images/gpu_usage.png)
![Average Validation Accuracy](https://github.com/rohit0906/monk_task/blob/master/images/average_val_accuracy.png)
