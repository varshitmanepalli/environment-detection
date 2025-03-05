# environment-detection
# Environment Detection

## Overview

This repository contains the implementation of an environment detection model using machine learning techniques. The goal is to classify different environments (e.g., indoor, outdoor, cluttered) and provide insights for self-care recommendations based on the detected environment.

## Research and Framework Selection

- Investigated existing frameworks and APIs for environment detection, including OpenCV and Google Cloud Vision API.
- Focused on environmental context recognition and its impact on self-care.
- Consulted UX researchers to refine the application use case.

## Data Collection

- Gathered images from various environments such as calm, cluttered, and outdoor.
- Collected images from public datasets and custom data sources.
- Labeled images accordingly for accurate classification.

## Model Development

- Implemented a Convolutional Neural Network (CNN) for environment classification.
- Experimented with different architectures and hyperparameter tuning for performance optimization.
- Converted the final model into TensorFlow Lite (.tflite) format for deployment.

## Feature Implementation

- Integrated self-care suggestions based on the detected environment.
- Example: If a park environment is detected, the system suggests outdoor mindfulness exercises or music.

## Repository Structure

```
|-- Environment_Detection.ipynb    # Main notebook for model training and evaluation
|-- pre-processing.ipynb           # Data preprocessing steps
|-- model.tflite                   # Trained TensorFlow Lite model
|-- labels.txt                      # Label mapping for classes
|-- README.md                       # Project documentation
```

## Dataset

A dataset containing labeled images of various environments is used for training the model. The dataset can be accessed from Kaggle.

## Installation and Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/environment-detection.git
   cd environment-detection
   ```
2. Run the Jupyter notebooks to train and test the model.

## Future Enhancements

- Improve model accuracy with additional data augmentation.
- Integrate real-time detection using edge devices.
- Extend functionality to suggest personalized self-care recommendations.

## Contributors

- **Varshit Manepalli**

## License

This project is licensed under the MIT License.
