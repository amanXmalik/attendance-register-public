# Attendance Register Project with Face Recognition using OpenCV
## Introduction
This project is a simple attendance register system implemented in Python using the OpenCV library for face recognition. The system captures images from a webcam, detects faces, and recognizes individuals to mark their attendance.

# Prerequisites
Before running the project, ensure you have the following dependencies installed:

Python 3.x
OpenCV (pip install opencv-python)
NumPy (pip install numpy)
# Usage
Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/your-username/attendance-register.git
Navigate to the project directory:

bash
Copy code
cd attendance-register
# Run the project:

bash
Copy code
python attendance_register.py
The webcam will be activated, and the system will start capturing frames.

Individuals' faces will be recognized, and their attendance will be marked.

Press 'Q' to quit the application.

# Configuration
You can customize the following parameters in the config.py file:

CASCADE_PATH: Path to the OpenCV Haarcascades for face detection.
DATA_PATH: Path to the directory where individual faces are stored.
THRESHOLD: The threshold for face recognition confidence.
# Adding Individuals
Add a new directory under data for each individual.

Capture multiple images of the individual's face under different lighting conditions.

Run the face_capture.py script to capture and store faces:

bash
Copy code
python face_capture.py --name John_Doe
Repeat the process for each individual.

# Troubleshooting
If you encounter issues with face recognition, you can adjust the threshold in the config.py file.

# Contributing
Feel free to contribute to the project by opening issues or submitting pull requests.

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
Thanks to the OpenCV community for providing powerful tools for computer vision.
Special thanks to contributors and users for feedback and improvements.
