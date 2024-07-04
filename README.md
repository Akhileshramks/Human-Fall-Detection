
# Human Fall Detection using YOLO

## Abstract

The "Fall Detection using YOLO (You Only Look Once)" project presents an innovative approach to real-time fall detection leveraging state-of-the-art object detection techniques. YOLO, a powerful object detection algorithm, is employed to accurately identify and locate individuals within video streams. The project focuses on the specific application of detecting falls, a critical scenario, and combines YOLO's efficiency with fall-specific training data. The system's architecture involves preprocessing video feeds, applying YOLO for object detection, and implementing fall classification algorithms.

## YOLO Overview

You Only Look Once (YOLO) is an end-to-end neural network that makes predictions of bounding boxes and class probabilities all at once. YOLO differs from previous object detection algorithms that repurposed classifiers to perform detection. YOLO is faster and more accurate, capable of detecting multiple objects in a single image.

## How to Run the Project

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Akhileshramks/Human-Fall-Detection.git
   cd Human-Fall-Detection
   ```

2. **Install Dependencies**:
   Ensure you have all the necessary dependencies installed. You can use the following command to install them:
   ```bash
   pip install -r requirements.txt
   ```

3. **Add Videos**:
   Place your video files in the `models/videos` directory. Ensure the videos are properly named and formatted.

4. **Run the Main Script**:
   Execute the main script to process the videos and generate the output:
   ```bash
   python main.py
   ```

5. **Check Output**:
   The processed video with fall detection annotations will be generated in the root directory.


For more details, please refer to the Report within the repository.
