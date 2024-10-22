# Single Object Detection Using CNN
## Overview
This repository showcases my project for detecting a single person in images using a deep Convolutional Neural Network (CNN). The model is trained on images gathered from the COCO dataset, specifically selected to contain only one person in each image. The primary goal is to establish a foundational approach toward multi-object detection.

## Project Journey
### Motivation
The motivation behind this project stemmed from my interest in object detection and the desire to build a lightweight and efficient model. I aimed to create a model that could detect individuals in images while minimizing computational complexity.

### Challenges Faced
* __Data Handling:__ Gathering and preprocessing data from the COCO dataset was challenging and time consuming. Ensuring that the images contained only one person require Consistency because of the size of annotation json file.  
* __Complexity Management:__ Training deep learning models is inherently resource-intensive. I faced memory constraints and had to optimize my model architecture for efficiency.  
* __Grayscale Conversion:__ Converting images to grayscale was a significant decision to reduce complexity. This approach helped simplify feature extraction but required thorough testing to ensure the model still performed well.  

## Achievements
* __Model Development:__ Successfully achieved accuracy on deep CNN architecture capable of predicting bounding boxes for single-person detection. The model consists of several convolutional layers, pooling layers, and fully connected layers.  
* __Efficiency Improvements:__ The decision to work with grayscale images significantly reduced computational load while maintaining acceptable performance levels.  
* __Foundational Step:__ This project serves as a solid stepping stone toward more complex multi-object detection tasks, laying the groundwork for future enhancements.  
## Sample Model Architecture
The architecture of the CNN model is designed to effectively capture features while remaining lightweight. Below is a brief overview of the architecture:

[![Screenshot (173)](https://github.com/user-attachments/assets/d5664162-e3e6-40de-9404-65715410f885)](https://www.kaggle.com/code/nishantsingh96/peronscoco)
[![Screenshot (174)](https://github.com/user-attachments/assets/c6ef578b-4966-45b1-b7b8-90aa4a19800f)](https://www.kaggle.com/code/nishantsingh96/peronscoco)


The model has demonstrated promising results in predicting bounding boxes for single-person images. Visualizations of the predicted bounding boxes can be found in the repository.

## Future Directions:

* Expand the model to support multi-object detection.
* Explore more advanced techniques, such as Vision Transformer and more deep CNN's for effective feature extraction, to enhance accuracy and efficiency.
* Experiment with data augmentation methods to improve model robustness and generalization.
