# Traffic Sign Recognition Using Various Deep Learning Models 

### Project Overview

This project focuses on classifying traffic signs using deep learning models. Multiple architectures, including a custom CNN and pretrained models, were trained and compared based on accuracy, F1 score, and training time.

### Models tested:

1. Custom CNN
2. VGG16 Transfer Learning
3. ResNet50 Transfer Learning
4. MobileNetV2

### Dataset

German Traffic Sign Recognition Benchmark (GTSRB)

### Technologies Used:
1. Python
2. TensorFlow / Keras
3. OpenCV
4. NumPy
5. Matplotlib

### Model Performance

| Model               | Accuracy (%) | F1 Score | Training Time (min) |
|--------------------|-------------|----------|---------------------|
| Custom CNN         | 97.61       | 0.9618   | 6.13                |
| VGG16 Transfer     | 87.66       | 0.8487   | 15.07               |
| MobileNetV2        | 71.65       | 0.6233   | 4.64                |
| ResNet50 Transfer  | 66.31       | 0.6238   | 8.20                |

### Key Findings

1. The Custom CNN achieved the highest accuracy and F1 score.
2. Transfer learning models showed mixed performance on the dataset.
3. MobileNetV2 trained fastest among pretrained architectures.
4. Model performance depends heavily on dataset characteristics and preprocessing.

### Future Developments

1. Hyperparameter tuning
2. Data augmentation
3 Real-time traffic sign detection
4. Deployment using Flask or Streamlit

### Author

Vigash Kumar


   
