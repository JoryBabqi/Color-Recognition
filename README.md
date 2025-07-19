# Color Recognition Project

This project is a simple **real-time color recognition program** using Python and OpenCV.  
It detects the color at the center of the webcam feed and displays its name (e.g., Red, Green, Blue, etc.) on the screen.

---

# Features
- Detects the color in real time from your webcam.
- Displays the detected color name on the video feed.
- Uses the **HSV color space** for better accuracy.
- Press 'q' to quit the program.

---

# How It Works
1. The program opens your default webcam.
2. It continuously checks the pixel color at the center of the screen.
3. The pixel is converted from **BGR to HSV** format.
4. Based on the HSV value, it classifies the color into categories like:
   - Red
   - Green
   - Blue
   - Yellow
   - Purple
   - White/Gray/Black

The detected color name is displayed at the top of the video feed.

---

# Requirements
Make sure you have the following installed:
- Python 3.x
- OpenCV
- NumPy
