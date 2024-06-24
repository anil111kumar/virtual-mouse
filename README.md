# Virtual Mouse
#By Anil kumar behera (MCA Khallikote unitary unversity):-------------
    A simple virtual mouse using OpenCV and Python. This project uses OpenCV to track the movement of a colored object (in this case, a hand) and translates it into mouse movements and clicks. 

## Features

- Hand tracking and finger detection using OpenCV.
- Mouse movement, left click, right click, double click, scroll, and volume control based on hand gestures.
- Smooth mouse movement for a more natural experience.

## Installation

To run this project, you'll need to have Python installed along with some required libraries. Follow the steps below to set up your environment.

### Prerequisites

- Python 3.7 or later
- OpenCV
- NumPy
- PyAutoGUI
- Pynput
- pyttsx3 (optional for text-to-speech functionality)

### Installing Required Libraries

You can install the required libraries using `pip`. Open your terminal or command prompt and run:

```bash
pip install -r requirements.txt
====================================================
Alternatively, you can install them one by one:



pip install opencv-python
pip install numpy
pip install pyautogui
pip install pynput
pip install pyttsx3  # Optional
====================*==================
HandTrackingModule
This project uses a custom module for hand tracking. Ensure you have the HandTrackingModule.py script in your project directory.

Usage:-

Run the following command to start the virtual mouse:
bash:-
    python3 main.py
==============================================
Overview
    The main functionality of the virtual mouse is implemented in virtual_mouse.py. Here's a brief overview of the key parts of the code:

Video Capture: Captures video from the webcam.
Hand Tracking: Uses HandTrackingModule to detect and track hand landmarks.
Gesture Recognition: Detects specific hand gestures to perform mouse actions like moving the cursor, clicking, and scrolling.
Volume Control: Uses gestures to control the system volume.
Key Gestures:-
   Index Finger Up: Move the mouse.
   Index and Middle Finger Up: Right click.
    Thumb and Index Finger Up: Left click.
    All Fingers Up: Scroll down.
    Four Fingers Up: Scroll up.
    Thumb, Index, and Middle Finger Up: Double click.
    Thumb and Index Finger Close Together: Volume control.
    *********************************************
Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request or open an issue.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
The hand tracking module is inspired by various online resources and tutorials on OpenCV and MediaPipe.
Special thanks to the contributors of the libraries used in this project.
Contact
For any questions or feedback, feel free to contact me at [beheraanilkumar917@gmail.com].
****************++++++++++++************************