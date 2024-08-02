# Asanyukta Mudras Kathak Detection Model

Welcome to the **Kathak Mudra Detection Model** repository, where tradition meets technology. This project is designed for both Kathak enthusiasts and developers interested in the intersection of classical dance and computer vision.

## Overview

Kathak, a classical dance form from India, relies heavily on precise hand gestures known as *Asamyukta Hasta Mudras*. These single-hand gestures are vital in conveying emotions and storytelling within the dance. However, mastering these intricate gestures can be challenging, especially for students and practitioners without constant access to expert guidance.

This repository hosts a powerful model trained using YOLOv8, specifically designed to detect and analyze these mudras in real-time. Our model is built on a fully customized dataset, ensuring it meets the unique requirements of Kathak hand gesture recognition.

![Asanyukta Mudras Kathak Detection Model](https://github.com/Demon-2-Angel/Mudra-Detection-for-Kathak-using-Yolov8-Object-Detection/blob/main/AsanyuktaKathakMudra.gif)
## Why This Model Matters

### For Kathak Practitioners:
- **Real-Time Feedback**: The model provides instant analysis of your hand gestures, helping you correct and perfect your mudras during practice.
- **Enhanced Learning**: It serves as a valuable tool for self-improvement, especially for dancers who may not have immediate access to expert guidance.

### For Developers:
- **State-of-the-Art Training**: The model leverages the latest advancements in object detection through YOLOv8, offering a sophisticated solution to a unique problem.
- **Custom Dataset**: This model was trained on a dataset specifically curated and annotated for Kathak hand gestures, providing a niche application of computer vision.
- **Cultural Significance**: This project is not just about technology; it’s about preserving and enhancing a classical art form, offering an opportunity to contribute to a culturally significant initiative.

## Explore the Model and Dataset

You can explore the trained model and the dataset used for training on RoboFlow:

- **RoboFlow Project:** [Kathak Trainer](https://universe.roboflow.com/aniruddha-jmp5a/kathak-trainer)

  - **Visualize the Dataset**: See the images and annotations used to train the model.
  - **Test the Model**: Run the model on sample images to see how it performs on different mudras.
  - **Download the Dataset**: If you're interested in working with the dataset, you can download it directly from RoboFlow.

## Technical Details

- **Framework**: YOLOv8 - Known for its speed and accuracy in object detection tasks.
- **Dataset**: Fully customized dataset of Asamyukta Hasta Mudras, carefully annotated to capture the nuances of each gesture.
- **Model Capabilities**: Detects and classifies all Asamyukta Hasta Mudras with high precision, providing posture analysis and feedback.

## Project Structure

- **Training the Model**: The model is trained using YOLOv8, with custom settings to optimize detection performance for the specific mudras in the dataset.
- **Validation and Testing**: Post-training, the model is validated and tested using different performance metrics to ensure reliability.
- **Deployment**: The model is deployed for real-time inference, where it can be used with video inputs to detect and annotate mudras.

## How to Use

1. **Clone the Repository**:
   ```
   bash
   git clone https://github.com/Demon-2-Angel/Mudra-Detection-for-Kathak-using-Yolov8-Object-Detection.git
   cd kathak-mudra-detection
   ```
2. ## Install Dependencies:
Install the necessary Python packages and other dependencies.

```
bash
pip install -r requirements.txt
```

3. ## Train the Model
Follow the provided Jupyter Notebook (`Kathak-Trainer - Mudra Detection.ipynb`) to train the model on your own dataset or resume training using the existing weights.

4. ## Run Inference
Use the provided pipeline to perform inference on video data, and visualize the detected mudras with annotated bounding boxes.

5. ## Deploy the Model
After training, deploy the model for real-time applications or further development.

## Key Sections of the Code
- **Installing Dependencies**: Ensures all necessary libraries like Roboflow, Ultralytics, OpenCV, etc., are installed and ready for use.
- **Training on Custom Dataset**: The model is trained using a dataset downloaded from Roboflow, which is specifically prepared for detecting Kathak mudras.
- **Inference Pipeline**: A custom inference pipeline is set up to process video input and display detected mudras in real-time.
- **Handling Performance Issues**: Adjustments like changing IoU thresholds and fine-tuning epochs are made to improve the model's performance on specific metrics like mAP50-95.

## Contributing
We welcome contributions from developers and Kathak enthusiasts alike. Whether it's improving the model's accuracy, expanding the dataset, or integrating new features, your input is valuable.

## Future Directions
- **Expand Dataset**: We aim to include more variations and nuances in mudra execution.
- **Cross-Platform Integration**: Developing plugins for real-time feedback during live performances or practice sessions.
- **Community Engagement**: Collaborating with Kathak institutions to refine and adapt the model further.

## Get Involved
This project is a fusion of art and technology, and we invite both developers and Kathak practitioners to collaborate, contribute, and take this model to the next level. Your contributions can make a significant impact in bridging the gap between tradition and modernity.

