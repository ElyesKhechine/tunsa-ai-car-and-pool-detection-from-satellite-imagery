# Car and Pool Detection Using Satellite Imagery

### TUNSA AI

**Technologies:** Python, CUDA, XML, COCO Format, Faster R-CNN, MMdetection, MMCV, Transfer Learning, Hyperparameter Tuning

## Introduction

This project focuses on the development of advanced object detection algorithms using satellite imagery. Leveraging state-of-the-art machine learning methodologies, it aims to accurately detect cars and pools in satellite images, facilitating various applications including urban planning and environmental monitoring.

## Project Scope

The project was conducted by members of TUNSA's AI team from July 7, 2022, to July 10, 2022. It involved research, implementation, and optimization phases.

## Technical Details

- **Automated Data Preprocessing Pipeline**: Implemented a robust data preprocessing pipeline converting XML annotations to COCO format, improving standardization and facilitating model training.
- **Optimized Faster R-CNN Model**: Utilized MMdetection and MMCV frameworks to optimize a Faster R-CNN model for object detection, achieving a notable 27% improvement in mean average precision (mAP).
- **CUDA-supported Operations**: Leveraged CUDA-supported operations during training for optimized bounding box prediction, significantly enhancing speed and efficiency.
- **Transfer Learning Methods**: Employed transfer learning techniques to accelerate model training, resulting in a 21% reduction in validation inference time.
- **Hyperparameter Tuning**: Fine-tuned model hyperparameters over 18 training epochs, leading to a 14% increase in detection accuracy for car and pool objects in satellite imagery.

## Project Colab Link

For detailed implementation and experimentation, please refer to the [project's Google Colab](https://colab.research.google.com/drive/1zG86MekBV1mmnvGVlLSHW2LRYOJGTXZr).

## Getting Started

### Installation

1. Ensure compatibility and setup of required software dependencies, including Python, CUDA, MMdetection, and MMCV.
2. Clone the project repository and navigate to the project directory.

### Usage

1. Run the provided scripts for data preprocessing and model training.
2. Monitor training progress and performance metrics to assess model accuracy.
3. Evaluate model inference on validation datasets to validate detection accuracy.

## License

This project is licensed under the [GPL-3.0 License](LICENSE).

## Contacts

For inquiries or collaboration opportunities, please contact:

- Elyes Khechine: elyeskhechine@gmail.com
- Hamza Kalfat: hamzakalfat51@gmail.com
- Fatma Hafsa: hafsafatma49@gmail.com
