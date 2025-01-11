# Eye-blinks-counting
Eye Blink Detection System using OpenCV and dlib. It calculates the Eye Aspect Ratio (EAR) to detect and count blinks in real-time. This system can be used for applications like driver drowsiness detection, hands-free control, and health monitoring by tracking eye movements.


Technologies used 

Python 3.8 🐍: The primary programming language used to develop the eye blink detection system, providing a stable and efficient environment for building machine learning and computer vision applications.

Scipy Module 📊: Used for calculating distances between facial landmarks to compute the Eye Aspect Ratio (EAR), essential for detecting eye blinks.

Imutils Module ⚙️: A set of utility functions that simplify image processing tasks and video handling, helping with resizing and processing frames efficiently.

CMake Module 🔧: Used to compile and manage the dependencies for the project, ensuring proper linking and building of libraries required by other modules like OpenCV and dlib.

DLIB Module 🤖: A toolkit used for machine learning and computer vision tasks, such as face detection and landmark prediction, enabling the identification of eyes in real-time video streams.

OpenCV Module 🖼️: OpenCV is used for image processing, including capturing video frames, converting frames to grayscale, drawing contours around eyes, and displaying results.

Wget 🌐: A command-line tool used to download external files, like the pre-trained facial landmark detection model, ensuring the necessary files are available for the system to function properly.



