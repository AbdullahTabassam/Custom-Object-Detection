# Object Detection Model for Bird Species Identification

This repository contains code for training two custom object detection models that can identify four different species of birds commonly found in the UK: Pica pica (Eurasian magpie), Erithacus rubecula (European robin), Turdus merula (Common blackbird), and Periparus ater (Coal tit).

The models are based on two different algorithms: ResNet101 Faster R-CNN and ResNet101 SSD. The repository includes five Jupyter notebooks that divide the code for preprocessing the data, training the models, and evaluating their performance.

Please note that the dataset is not included in the repository. However, it can be provided upon request to interested researchers and developers. The training data consists of annotated images of the four bird species. The images in the dataset are collected by CSM department of Liverpool Jhon Moores University. The annotations are in the COCO format and include bounding boxes around the birds.

Each Jupyter notebook corresponds to a specific stage of the object detection pipeline, including data preparation, model training, evaluation, and inference. The ResNet101 Faster R-CNN and ResNet101 SSD models are suitable for real-time object detection, and researchers can choose the model that suits their application based on the required balance between speed and accuracy.

The trained models can be used for a variety of applications, such as wildlife monitoring and conservation efforts.
Installation

To install and use the code in this repository, 

    Clone this repository: git clone https://github.com/AbdullahTabassam/Custom-Object-Detection