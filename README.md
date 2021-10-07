# Covid-19-Chest-X-ray

## Introduction:
In the recent pandemic, it is essential to get diagnosis fast to prevent cross-contamination in hospitals and start early treatment to save patients’ life. Diagnosis of Covid from X-ray is faster than any other lab test. 

## Problem Statement:
Build a classification model to Diagnosis of Covid from X-ray.

## Data preparation:

•	Removed null values from the dataset.

•	Redistibuted test and train data split.

•	Used augmentation techniques like adjusting brightness, zooming, random cropping, rotating, and flipping the images.


## Conclusion:-
Developed a CNN model with Alex-net architect and acquire the Recall rate of 72%. Which is better than a rapid antigen test.

Epoch 1/100
42/42 [==============================] - 735s 17s/step - loss: 491.4482 - TP: 2010.6047 - TN: 4846.3256 - FP: 774.4186 - FN: 799.7674 - AUC: 0.6906 - Recall: 0.6735 - val_loss: 9.8583 - val_TP: 873.0000 - val_TN: 2055.0000 - val_FP: 309.0000 - val_FN: 309.0000 - val_AUC: 0.7135 - val_Recall: 0.7386


Epoch 100/100
42/42 [==============================] - 344s 8s/step - loss: 1.8391 - TP: 2307.8140 - TN: 5089.0465 - FP: 436.2558 - FN: 454.8372 - AUC: 0.9005 - Recall: 0.8393 - val_loss: 1.7527 - val_TP: 878.0000 - val_TN: 2062.0000 - val_FP: 302.0000 - val_FN: 304.0000 - val_AUC: 0.7028 - val_Recall: 0.7428
