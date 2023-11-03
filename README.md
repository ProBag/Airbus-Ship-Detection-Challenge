# Airbus-Ship-Detection-Challenge

## What is Object detection?
Object detection is a computer technology that deals with detecting instances of semantic objects of a certain class, such as humans, buildings, or cars, in digital images and videos. It is related to computer vision and image processing and has many applications in various domains, including face detection and pedestrian detection. Object detection is useful in image retrieval and video surveillance, among other areas of computer vision.

<img width="734" alt="Screen Shot 2023-11-02 at 11 56 08 PM" src="https://github.com/ProBag/Airbus-Ship-Detection-Challenge/assets/143302669/3908dd46-58a4-4fac-8f55-0ae47b525b49">

## Description 

This project involves detecting ships in satellite images using the dataset provided by Airbus. 

To get started, download the training and testing images from the provided zip folders, along with the 'train_df.csv' file containing the image ID and corresponding ship pixels.

Next, visualize the training images with 0, 1, and 2 ships, highlighting the ship areas using pixel information from 'train_df.csv'. Also, plot some random images from the test set for visualization.

Perform object detection and submit the results in the format of the 'sample_submission.csv' file. Additionally, compute the Intersection over Union (IOU) of the results with the test set and include the results in the report.

To improve the results, experiment with pre-trained models such as Detectron2, RetinaNet, YOLO, and DETR (Choose among one). Show tables and graphs illustrating how the results change with different pre-trained models.

## Reference 
https://towardsdatascience.com/12-papers-you-should-read-to-understand-object-detection-in-the-deep-learning-era-3390d4a28891 
