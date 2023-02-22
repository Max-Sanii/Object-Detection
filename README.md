# Object-Detection on Scooters
The objective of the project is to train a pre-trained Yolo model to detect Electric Scooters. For this project, I used YOLOv4 model, which was already trained on the COCO dataset and can detect 80 common objects such as vehicle, bike, motorcycles, and etc. However, YOLOv4 is not trained on electric scooters, so I needed to re-train the model with scooter images so that it could be used to detect scooters.

## Description
The Application consists of three sections:

### Example 1
![sampleDetection2](https://user-images.githubusercontent.com/118564295/220785252-30c18320-f319-4b79-92ef-0665b541fc84.JPG)

### Example 2
![sampleDetection4](https://user-images.githubusercontent.com/118564295/220785286-79463729-4495-4693-a25f-2c1d5d4a6b23.JPG)

### Example 3
![sampleDetection6](https://user-images.githubusercontent.com/118564295/220785320-c89b81de-902b-47da-af78-62328e0045a1.JPG)

### Technologies
* YOLOv4: the pre-trained weights and configuration file.
* Darknet: an open-source framework for training YOLO models.
* Google Collab: used for running Darknet and training Yolo.
* LabelImg: used for image annotation.
* Python
* OpenCV
* Numpy
* Matplotlib


### Instructions:
The application is created by Dash framework in python, the file “my_diabetesp-prediction-app.py” contains the whole code including both the logic and the layout of the app. 
To run the app, first download the files, and we just need to run the below python command, and then the app will be serving in the localhost. (We also need to set the path of the csv file)
Python predict-diabetes-app.py

### Data source:
This dataset was downloaded from data.world which came from the Biostatistics program at Vanderbilt.
The downloaded dataset contains 390 instances (patients) including 60 instances are diabetes and the remaining 330 are not diabetes.
