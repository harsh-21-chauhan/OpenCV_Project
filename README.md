## Optical Flow

### Problem Statement

#### Subtask 1: CJ NEEDS HELP! – Implementing Optical Flow

You are expected to implement the Lucas–Kanade sparse optical flow estimation algorithm as described in the following article:  
https://nanonets.com/blog/optical-flow/

The implementation is carried out on video clips of your choice selected from the provided video. You are allowed to use basic OpenCV functions such as `cv2.imread`, `cv2.imshow`, etc., and may additionally use `cv2.goodFeaturesToTrack`. You may refer to the official OpenCV documentation for guidance.

### Solution Overview

The solution for Task 1 is implemented in  
`TASK_1/mainCode.py`

It utilizes the Lucas–Kanade sparse optical flow algorithm to detect and visualize motion vectors between consecutive frames of an input video.

### Key Features
- Detects strong corner features in the initial frame for tracking.
- Computes optical flow to track these features across consecutive frames.
- Visualizes motion vectors using lines representing the direction and magnitude of motion.
- Displays the processed video frames with motion vectors in real time.

### Input
- Video file: `TASK_1/Input_Video_Task_1/OPTICAL_FLOW.mp4`

### How to Run
1. Ensure Python is installed along with the required libraries (OpenCV, NumPy).
2. Navigate to the repository’s root directory.
3. Run the script using the following command:

```bash
python TASK_1/mainCode.py
