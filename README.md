# VisDrone-YOLO-Efficient-Object-Detection-for-Drone-Captured-Imagery

VisDrone-YOLO is a state-of-the-art project designed to perform object detection and classification on drone-captured imagery using YOLO (You Only Look Once) models. The project leverages the VisDrone dataset and applies modern techniques for dataset preparation, annotation conversion, and fine-tuning YOLO models for high-performance object detection.

---

## Key Features

- **Dataset Preparation**:
  - Automated download and setup of the VisDrone dataset (train, validation, and test splits).
  - Conversion of VisDrone annotations into YOLO format for seamless training integration.

- **YOLO Model Fine-Tuning**:
  - Training the YOLO11l model using multi-GPU setups for efficient computation.
  - Achieved optimized performance using techniques like mixed precision training.

- **Object Detection Classes**:
  - The model is fine-tuned to detect 10 object classes (e.g., pedestrians, cars, bicycles, trucks, buses, etc.) in drone imagery.

- **Performance Metrics**:
  - Precision (P), Recall (R), and mAP (mean Average Precision) are tracked across training and validation phases.
  - Robust metrics visualization including PR curves, F1-score trends, and mAP graphs.

- **Training Optimization**:
  - Implemented adaptive learning rates, augmentation techniques, and optimized hyperparameters for peak performance.

