# angle-between-two-colors
# Angle Measurement from Video and using camera

This Python script reads a video file and detects objects of specified colors using HSV color space thresholding. It then calculates and displays the angle between the detected objects in the video frames.

## Features

- Detect objects of specified colors using HSV color space thresholding.
- Measure the angle between the detected objects in each frame of the video.
- Display the annotated video with the measured angle.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- imutils

## Usage

1. Place your video file in the same directory as the script or provide the path to your video file.
2. Run the Python script `angle_color.py`.
3. The script will read the video file frame by frame and detect objects of specified colors using HSV color space thresholding.
4. It will calculate the angle between the detected objects and display the annotated video with the measured angle.
5. Press any key to advance to the next frame. Press 'q' to exit the program.

## Configuration

- Modify the HSV lower and upper bounds for each color in the `find_color1()` and `find_color2()` functions according to the colors you want to detect.
- Adjust the threshold values for contour area in the `find_color1()` and `find_color2()` functions to filter out small contours.
