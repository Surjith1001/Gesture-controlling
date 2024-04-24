# Controlling PC by Hand Gesture
Gesture Encodings: Enumerations for representing different hand gestures, such as fist, palm, thumb, etc. These are used to classify and interpret the detected gestures.

Hand Recognition: The HandRecog class processes hand landmarks obtained from MediaPipe to recognize gestures based on the configuration of fingers and hand positions.

Controller: This class contains methods for executing actions corresponding to detected gestures, such as moving the cursor, clicking, scrolling, and adjusting system settings like brightness and volume.

Gesture Controller: The main class that orchestrates the entire process. It initializes the video capture, processes the frames, detects hand landmarks, classifies the hands, recognizes gestures, and triggers the corresponding actions.

Main Loop: The script continuously captures video frames from the webcam, processes them for hand tracking and gesture recognition, and updates the system accordingly until the user terminates the program.

libraries Used :
OpenCV (cv2),
MediaPipe (mediapipe),
PyAutoGUI (pyautogui),
Math (math),
Enum (enum),
ctypes,
comtypes,
pycaw,
screen_brightness_control (screen_brightness_control),
Google Protobuf (google.protobuf.json_format).

<img src="">
