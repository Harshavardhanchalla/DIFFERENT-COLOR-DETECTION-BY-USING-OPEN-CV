# DIFFERENT-COLOR-DETECTION-BY-USING-OPEN-CV


Project Title
Color Detection with OpenCV

Project Description
This project uses OpenCV to capture video from a webcam and detect specific colors (red, blue, green) within the video feed. It then creates masks for these colors and displays them in separate windows. Additionally, it provides a mask for detecting all colors except white. This project demonstrates the use of color space conversion, masking, and bitwise operations in OpenCV.

Table of Contents
Installation
Usage Instructions
Credits
Installation
Clone the repository:

sh
Copy code
cd color-detection-opencv
Install required libraries:
Make sure you have Python installed. Then, install the necessary libraries using pip:

sh
Copy code
pip install numpy opencv-python
Ensure you have a webcam connected:
The project uses the default webcam (device 0). Make sure your webcam is properly connected and working.

Usage Instructions
Run the script:
Execute the Python script to start the color detection.

sh
Copy code
python color_detection.py
Interacting with the program:

The program will open multiple windows displaying the original video feed and masks for red, blue, green, and all colors except white.
Press the Esc key to exit the program.
Code Explanation
The code captures video frames from the webcam, converts them to HSV color space, and creates masks for specific color ranges (red, blue, green). It then applies these masks to the original frame using bitwise operations and displays the results in separate windows.

Credits
This project uses the following libraries:

OpenCV for image and video processing.
NumPy for numerical operations.
Additional Notes
You can modify the color ranges in the code to detect different colors.
Adjust the HSV values as needed to fine-tune the color detection for your specific lighting conditions and camera settings.
Feel free to fork this repository, contribute, or report any issues. Thank you for checking out this project!
