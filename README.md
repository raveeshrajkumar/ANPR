# ANPR
Automatic Number Plate Recognition


This project aims to develop an Automatic Number Plate Recognition (ANPR) system using computer vision techniques. The system is capable of accurately detecting license plates from images, segmenting characters from the detected plates, and recognizing the characters using Optical Character Recognition (OCR) methods.

## Team Members

- Raveesh R
- Akshay S.G
- Samyuktha S


## Dataset

The project utilizes the following datasets for training and testing the ANPR system:

- [Indian License Plates](https://www.kaggle.com/datasets/thamizhsterio/indian-license-plates)
- [Indian Vehicle License Plate Dataset](https://www.kaggle.com/datasets/saisirishan/indian-vehicle-dataset)

The datasets consist of images containing vehicles with visible license plates, covering various scenarios such as different lighting conditions, angles, and vehicle types.

## Approach

The ANPR system follows the following steps:

1. **License Plate Detection**: The system uses Haar cascades to detect license plates in input images.
2. **Image Processing and Display**: The detected license plates are extracted and displayed.
3. **Character Segmentation**: Individual characters from the detected license plate image are segmented using contour detection and image processing techniques.
4. **Optical Character Recognition (OCR)**: Two OCR methods are employed:
   - **EasyOCR**: A library for text recognition that directly extracts text from segmented characters.
   - **Convolutional Neural Network (CNN)**: A custom CNN model is trained on a dataset of character images to predict the characters with potentially higher accuracy.


## Future Plans

- Expand the project to support ANPR from video data, enabling real-time license plate detection for moving vehicles.
- Implement algorithms for object tracking and frame-by-frame analysis.
- Integrate with existing traffic management systems for automatic detection of traffic violations, such as speeding or running red lights.
- Incorporate machine learning models trained on diverse datasets to improve accuracy and robustness in challenging conditions.
- Market the system as a comprehensive surveillance solution for traffic management and law enforcement.

## License

This project is licensed under the [MIT License](LICENSE).



