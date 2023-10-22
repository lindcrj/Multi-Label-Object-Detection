# Multi-Label Object Detection Project
**Project Director:** Jung-Ching Chen

**Tools:** Python

## Project Overview

This project centers around the development of a multi-label object detection system with a primary focus on self-driving car applications. Leveraging state-of-the-art techniques and deep learning frameworks, we aimed to create an efficient and accurate system for identifying and classifying multiple objects within a single image.


## Project Objectives

1. **Data Preparation and Organization:**
   - The project began by structuring and organizing the dataset collected for self-driving car object detection. This crucial step ensured data readiness for model training and evaluation.

2. **YOLOv5 Integration:**
   - We integrated the YOLOv5 model architecture, a popular real-time object detection framework, as the core component of our system. This choice was made due to its speed and accuracy.

3. **Linear SVM for Object Classification:**
   - In addition to detection, the project included the use of Linear Support Vector Machines (SVM) for object classification. This enabled our system to predict and assign labels to detected objects.

4. **Achieving High Accuracy:**
   - Our primary objective was to achieve an object detection and classification accuracy rate of over 80%. This accuracy threshold was set to meet the high safety and reliability standards required in self-driving car technology.

5. **Real-Time Processing:**
   - We aimed to ensure that the system was capable of real-time multi-object detection, with a remarkable prediction speed of just 0.01 seconds per image. Achieving real-time processing is crucial for practical deployment in self-driving vehicles.

## Technical Details

- **Data Organization:** The project involved meticulous data organization and structuring to create a consistent and reliable dataset for training and testing purposes.

- **Deep Learning Framework:** We have leveraged the capabilities of the PyTorch framework, a powerful and flexible library for machine learning and deep learning, to build and train our custom object detection model.

- **Model Quantization:** To optimize the model for real-time inference, we implemented model quantization techniques. This process allowed the model to run efficiently on hardware devices while maintaining high accuracy.

- **GPU Acceleration:** We utilized GPU acceleration, specifically a Tesla T4 GPU, to expedite model training and real-time processing. This hardware acceleration was crucial for meeting the speed requirements of self-driving applications.

## Achievements

- Successful integration of YOLOv5 and Linear SVM for object detection and classification.
- Achieved an object detection and classification **accuracy rate exceeding 80%**.
- Implemented model quantization techniques to achieve real-time multi-object detection with a remarkable **prediction speed of just 0.01 seconds per image**.

## Next Steps

The success of this project forms the foundation for further advancements in self-driving car technology. Future work may include additional optimizations, the incorporation of more complex scenarios, and the integration of real-time decision-making capabilities to enhance self-driving car safety and performance.

## Python Source Code
* [Yolov5](https://github.com/lindcrj/Multi-Label-Object-Detection/blob/379f2e84572d99fa1d5130d76bac07a30206323d/YOLOv5.ipynb)
  * The datasets used in our project were collected by ALIN CIJOV -> [datasets](https://www.kaggle.com/datasets/alincijov/self-driving-cars?fbclid=IwAR3_GP8QnHIusn7NDuKsz3MAE8iV7kIas6xa4SuyGIurer5wE2RIiGxX2Nw)
  
# Final Result
https://user-images.githubusercontent.com/96403274/219674850-73940ad2-14cb-411c-8d65-cd0d02c6c69c.mp4



