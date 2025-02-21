# Lane_detection
This project implements a real-time lane detection system using OpenCV and Python. It processes video input to identify and highlight lane markings on the road. 
The system employs several image processing techniques, including color conversion to grayscale, Gaussian blurring for noise reduction, and Canny edge detection to identify potential lane boundaries. 
A region of interest is defined to focus processing on the relevant area of the image, and Hough Transform is used to detect lines representing the lanes. The detected lines are then averaged and extrapolated to provide a stable and continuous lane marking overlayed onto the original video feed. 
The final output displays the original video with enhanced lane markings, assisting in tasks like autonomous driving or driver assistance systems.
