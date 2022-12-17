# ALPR
This paper presents an efficient and layout-independent Automatic License Plate Recognition (ALPR) system based on the state-ofthe-art YOLO object detector that contains a unified approach for license plate (LP) detection and layout classification to improve the recognition results using post-processing rules

Overview: The density of cars per city has been drastically increasing, and it is predicted that this number will keep on increasing in the upcoming years. Automatic License Plate Recognition (ALPR) has become a requirement for surveilling this huge car concentration not only efficiently but in real-time as well.

Automatic License Plate Recognition (ALPR) has been a frequent research topic due to its many practical applications. However, many of the current solutions still need to be robust in real-world situations, commonly depending on many constraints. 

This paper presents a robust and efficient ALPR system based on the state-of-the-art YOLO object detector.

A model with the combination of two Neural Networks has been constructed for the same. 
First, the incorporated Yolov5(a Convolutional Neural Network (CNN)) is customed trained and tuned for detecting License plates (LP) from different vehicles. Also, by using the easy-OCR model for extracting the text from the license plate. 

In addition to this, a further study can be done by comparing various combinations of different object detection and OCR models to find the optimum out of all.

The future application of this will not only help in the fast operations of cars at tolls, but a whole city network can be developed to monitor and evaluate multiple cars at the same time. Furthermore, it can help in improving the security and traffic management of the city.

Procedure:

1.	Detecting license plate:

I have used a dataset of license plate detection (“https://www.kaggle.com/datasets/andrewmvd/car-plate-detection?select=images”)

Here I have used roboflow for splitting and augmentation of data:
!()
