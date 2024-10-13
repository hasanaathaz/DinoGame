# DinoGame
To use computer vision to detect when an obstacle emerges and automatically hit the space button
Credit to: Murtaza's Workshop

# Automatic Game Playing Script with Obstacle Detection

This Python script automates gameplay by identifying obstacles in a specific region of the screen and triggering jumps accordingly. It utilizes OpenCV for image processing, cvzone for contour detection, mss for screen capture, and pyautogui for simulating keyboard presses.

Features:

Dynamic Obstacle Detection: Identifies obstacles within the defined screen area using image processing techniques.
Adaptive Jumping: Triggers jumps based on the proximity of the leftmost obstacle to a predefined threshold.
Customizable Region: Allows you to adjust the screen region of interest for the game.
FPS Display: Tracks and displays the script's frames per second for performance monitoring.
Requirements:

Python 3.x
OpenCV
cvzone
mss
pyautogui
Installation:

Bash
pip install opencv-python cvzone mss pyautogui
Use code with caution.

Usage:

Modify Region Coordinates:
Adjust the x, y, width, and height values in the capture_screen_region_opencv_mss function to define the screen area containing the obstacles.
Set Jump Distance:
Modify the jump_distance parameter in the game_logic function to control the trigger point for jumps based on obstacle distance from the screen edge.
Run the Script:
Execute the script using python main.py (assuming your main script is named main.py).
Note:

This script interacts with your system and simulates keyboard input. Use it responsibly and with caution, especially in online games where automated gameplay might be prohibited.
The script's effectiveness depends on the game's visual elements and may require adjustments for different scenarios.
Further Enhancements:

Implement more sophisticated object detection techniques (e.g., machine learning models) for better obstacle recognition.
Explore advanced game logic and control strategies based on game mechanics.
Feel free to contribute to this project by improving its functionality or adding new features!
