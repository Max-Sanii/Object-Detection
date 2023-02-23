# Object-Detection on Scooters
The objective of the project is to train a pre-trained Yolo model to detect Electric Scooters. For this project, I used YOLOv4 model, which was already trained on the COCO dataset and can detect 80 common objects such as vehicle, bike, and motorcycles; however, YOLOv4 was not trained on electric scooters, so I needed to re-train the model with scooter images so that the model could be used to detect scooters.

## Project Highlights
The project consists of the following steps:
* Prepare and pre-process the scooter images
* Download and configure a pre-trained YOLOv4 model
* Configure the Darknet framework to train YOLOv4 model
* Train YOLO with the images of electric scooter
* Perform object detection using the new trained model
* Count the number of scooters in an image

## Object-Detection Samples
#### Example 1
![sampleDetection2](https://user-images.githubusercontent.com/118564295/220839946-df04f146-c7b4-48d3-8af2-594f3a7cd784.jpg)

#### Example 2
![sampleDetection4](https://user-images.githubusercontent.com/118564295/220839976-5b07f6ca-8dee-4f88-9937-6bb3adec6c02.jpg)

#### Example 3
![sampleDetection6](https://user-images.githubusercontent.com/118564295/220840010-5592e65d-024a-4841-ad6c-115f6b65c89a.jpg)

## Image Pre-processing
#### Sample Distorted Image
![detected_scooters_1_new_test](https://user-images.githubusercontent.com/118564295/220840219-0ff161f3-9170-4d6a-8d3e-c7f96778556d.png)

#### Brightening
![image_1_brightened](https://user-images.githubusercontent.com/118564295/220840243-8bde5ab3-1f81-4ce0-b312-f097e580ca14.png)

#### Denoising
![image_1_brightened_denosied](https://user-images.githubusercontent.com/118564295/220840256-9ae8326f-e0c6-4f0e-8567-39037ab1d56f.png)

### Technologies
* YOLOv4: the pre-trained weights and configuration file.
* Darknet: an open-source framework for training YOLO models.
* Google Collab: used for running Darknet and training Yolo.
* LabelImg: used for image annotation.
* Python
* OpenCV
* Numpy
* Matplotlib

