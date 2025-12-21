# Optical Flow

## Problem Statement (Subtask 1: CJ NEEDS HELP!: IMPLEMENTING OPTICAL FLOW)

You are expected to implement the Lucas-Kanade sparse optical flow estimation algorithm specified in this article (https://nanonets.com/blog/optical-flow/) on clips of your choice from this video. You are allowed to use basic OpenCV functions: cv2.imread, cv2.imshow, etc., and you may additionally use cv2.goodFeaturesToTrack. You may refer OpenCV documentation.

The solution for Task 1 is implemented in TASK_1/mainCode.py. It utilizes the Lucas-Kanade sparse optical flow algorithm to detect and visualize motion vectors between consecutive frames of an input video.

## Key features:

Detects strong corners in the initial frame to track.
Calculates optical flow to track these corners in subsequent frames.
Visualizes the motion vectors (lines) on the video frames, showing the direction and magnitude of movement.
Displays the processed video with motion vectors in real-time.
Input Video

The script uses the following video file as input: TASK_1/Input_Video_Task_1/OPTICAL_FLOW.mp4

## How to Run

Ensure you have Python installed along with the necessary libraries (OpenCV, NumPy).
Navigate to the repository's root directory.
Run the script using the following command:
python TASK_1/mainCode.py
