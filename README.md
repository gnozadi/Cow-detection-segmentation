# Cow Detection and Segmentation

This project focuses on **detection and segmentation of cows** using deep learning models to process and analyze video data. The main goal is to accurately identify and segment cows in video frames using different versions of the **YOLO (You Only Look Once)** object detection algorithm: **YOLOv5**, **YOLOv6**, and **YOLOv7**.

## Overview

### Key Steps in the Project:
1. **Frame Extraction**: Videos are broken down into individual frames to create a dataset.
2. **Annotation**: Frames are annotated using the [makesense.ai](https://www.makesense.ai/) annotation tool to label cow instances.
3. **Dataset Splitting**: The annotated dataset is split as follows:
   - **Training Set**: 70%
   - **Testing Set**: 15%
   - **Validation Set**: 15%
4. **Model Training**: The dataset is trained using various versions of YOLO (v5, v6, v7) to compare performance and accuracy.

## Technologies Used

- **Python**: For data processing and model training.
- **YOLOv5, YOLOv6, YOLOv7**: State-of-the-art object detection models used for training and inference.
- **makesense.ai**: A web-based tool for image annotation.
- **OpenCV**: For video processing and frame extraction.

## Project Workflow

1. **Extract Frames from Videos**:
   - Utilize OpenCV to read videos and save frames as image files.
2. **Annotate Frames**:
   - Annotate frames using makesense.ai to create labeled data.
3. **Dataset Preparation**:
   - Organize annotated data into training, testing, and validation sets.
4. **Model Training**:
   - Train the dataset with YOLOv5, YOLOv6, and YOLOv7 models to compare their performance on cow detection and segmentation tasks.

## Installation and Setup

### Prerequisites
- **Python 3.x**
- **PyTorch**
- **OpenCV**
- **YOLOv5, YOLOv6, YOLOv7 repositories** or relevant implementations
- **makesense.ai** account for annotation


## Contributing

Contributions, suggestions, and improvements are welcome! Feel free to open issues or create pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
