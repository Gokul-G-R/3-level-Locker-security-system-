# 3-level-locker-security-system-
3-Level Locker System
This project implements a secure 3-level locker system, providing enhanced security through multiple layers of authentication:

1. Level 1: Keypad Authentication
The first level of security is a numeric keypad, where the user enters a predefined passcode. This step ensures basic access control.

2. Level 2: OTP (One-Time Password) via GSM
Upon successfully entering the passcode, an OTP is generated and sent to the user’s mobile phone via a GSM module. The user must enter the received OTP to proceed to the next level.

3. Level 3: Face Recognition using OpenCV
The final level of security involves face recognition. Using OpenCV, the system captures and verifies the user’s face against a pre-trained model to grant access. This ensures that only authorized individuals can unlock the system.

Features:
Multi-level authentication for enhanced security.
GSM module for real-time OTP generation and delivery.
OpenCV-based face recognition for robust identity verification.
Modular code structure for easy integration and future enhancements.
Technologies Used:
Hardware: Keypad, GSM module, 16X2 LCD display 
Software: Arduino IDE, OpenCV for face recognition

