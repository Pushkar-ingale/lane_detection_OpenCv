Lane Detection using OpenCV and MoviePy
This Python script detects lane lines in a video using computer vision techniques implemented with OpenCV library. It processes each frame of the input video, identifies lane lines, and draws them on the frames, producing an output video with lane lines annotated.

Requirements
Python 3.x
OpenCV (opencv-python package)
MoviePy (moviepy package)
You can install the required packages using pip:

pip install opencv-python moviepy
Usage
Clone or download this repository to your local machine.

Navigate to the directory containing the code.

Place your input video file (e.g., test2.mp4) in the same directory.

Run the script lane_detection.py with the following command:

python lane_detection.py
This will process the input video, detect lane lines, and save the annotated output video as output.mp4.

Customization
You can customize various parameters in the script to adjust the lane detection algorithm's behavior:

Region of Interest: Modify the vertices in the region_selection function to define the region of interest where lane lines are expected to appear.

Hough Transform Parameters: Adjust parameters such as threshold, minLineLength, and maxLineGap in the hough_transform function to fine-tune line detection sensitivity.

Canny Edge Detection Thresholds: Tune the low_t and high_t thresholds in the frame_processor function to control edge detection sensitivity.

Credits
This project is inspired by various tutorials and resources on computer vision, OpenCV, and lane detection algorithms.

OpenCV Documentation
MoviePy Documentation
