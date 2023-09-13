# Real-time-Face-and-Smile-Detection-and-Image-Capture

Description:

This GitHub project is a Python-based computer vision application that leverages the OpenCV library to perform real-time face and smile detection through a webcam feed. The program detects faces and smiles in the live video stream, outlines them with rectangles, and captures images when both face and smile are detected. The primary goal of this project is to provide a simple example of real-time computer vision and object detection.

**Key Features:**

1. **Face Detection:** The project uses the Haar Cascade Classifier to detect human faces in the video feed. When a face is detected, it draws a rectangle around it.

2. **Smile Detection:** In addition to face detection, the program also includes smile detection using another Haar Cascade Classifier. When a smile is detected within a detected face, it draws another rectangle to highlight the smile.

3. **Image Capture:** The program captures images when both a face and a smile are detected simultaneously. These images are saved to the specified directory.

4. **Live Video Feed:** The application provides a live video feed with real-time detection and visual feedback. The feed is displayed in a window that can be easily closed by pressing 'q'.

**Usage:**

1. Clone or download the repository to your local machine.

2. Ensure you have Python and OpenCV installed.

3. Run the script, and it will activate your webcam, displaying the live video feed.

4. When both a face and a smile are detected in the video feed, an image will be captured and saved to the specified directory.

5. Press 'q' to exit the program.

This project is an excellent starting point for anyone interested in computer vision, object detection, or exploring the capabilities of OpenCV. Feel free to fork, modify, and enhance this code for your specific needs or use it as a learning resource for your computer vision projects.
