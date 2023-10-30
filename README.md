
# MoveNet Pose Estimation Jupyter Notebook

This Jupyter Notebook demonstrates how to perform real-time human pose estimation using the MoveNet model. Please follow the instructions below to run the code.

## Prerequisites

Before running the notebook, make sure you have the following prerequisites installed:

- Python (3.7 or higher)
- Jupyter Notebook
- TensorFlow (2.x)
- OpenCV (cv2)

## Getting Started

1. Clone this repository to your local machine.

2. The MoveNet model file (e.g., `movenet_lightning.tflite`) is already included in this repository and is available in the same directory as this notebook.

3. Open the Jupyter Notebook by running the following command in your terminal:

   ```bash
   jupyter notebook MoveNet_Pose_Estimation.ipynb
   ```

4. Execute the notebook cells one by one to run the code.

## Notebook Contents

The notebook contains the following sections:

- Importing Libraries
- Load the MoveNet Model
- Video Capture and Preprocessing
- Pose Estimation
- Rendering the Results
- User Interaction and Exit

## References

- Official MoveNet (BlazePose) model on TensorFlow Hub:
  [https://tfhub.dev/google/lite-model/movenet/singlepose/lightning/3](https://tfhub.dev/google/lite-model/movenet/singlepose/lightning/3)

- TensorFlow Hub Documentation:
  [https://www.tensorflow.org/hub](https://www.tensorflow.org/hub)

- OpenCV Documentation:
  [https://opencv.org/](https://opencv.org/)

