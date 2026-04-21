# SafeDrive
SAFE DRIVE -DRIVER DROWSINESS DETECTION SYSTEM This project implements a Driver Drowsiness Detection System using computer vision techniques. It monitors the driver's facial features in real-time to detect signs of drowsiness such as prolonged eye closure or yawning and issues an alert to prevent accidents.

FEATURES :- Real-time detection of eyes and mouth using Haar Cascades. Alerts when: Eyes are closed for a prolonged period. Mouth is open continuously (indicative of yawning). Uses webcam input for live monitoring. Audio alarm for immediate warning.

TECHNOLOGIES USED :- Python OpenCV Haar Cascade Classifiers NumPy Playsound (for alarm) Matplotlib (for visualization)

WORKING :- Captures video from your webcam. Detects facial landmarks using Haar cascades. Counts frames with closed eyes or open mouth. Triggers an alarm if drowsiness signs are detected consistently.
