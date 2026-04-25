This is a Hand Gesture-Controlled Presentation System that uses computer vision to turn a standard webcam into a touchless controller. By detecting specific finger patterns and hand movements, it allows a presenter to navigate slides, annotate content in real-time, and zoom into details without ever touching a mouse or keyboard.

# Key Components:
Navigation: Uses hand positioning relative to a virtual threshold to switch slides.

Annotation: Implements a drawing engine that supports multiple colors and "Undo/Clear" functions triggered by finger counts.

Dynamic Zoom: Uses a linear interpolation (Lerp) algorithm to create a smooth, cinematic zoom-in effect based on hand height.

Virtual Pointer: A stabilized "laser pointer" that follows the index finger using a smoothening filter to prevent jitter.

Automation: Includes a gesture-based screenshot utility to save annotated slides instantly.

It is designed for professionals and educators looking for a more interactive, futuristic way to deliver presentations.

# AI Gesture-Controlled Presentation System
This project is a computer-vision-based presentation tool that allows users to control slides, draw annotations, zoom in on specific areas, and save screenshots—all using hand gestures via a webcam.

## Features
* **Virtual Pointer:** Smoothly track your index finger as a red laser pointer.
* **Slide Navigation:** Swipe left or right above a set threshold to change slides.
* **Dynamic Drawing:** Draw on slides in multiple colors (Red, Green, Blue).
* **Smooth Zooming:** Use hand height to zoom into slide content with a seamless glide effect.
* **Annotation Management:** Undo specific lines or clear the entire screen with gestures.
* **Auto-Save:** Capture the current slide with your drawings and save it to your local drive.


## Gesture Guide

Action-Gesture-Description

**Pointer**  (Index + Mid finger up) Move your index finger to control the red pointer. 
**Draw**  (Hold index finger) Hold your index finger up for a few frames to start drawing. 
**Next Slide**  (Pinky finger up) Raise hand above the blue threshold line and extend the Pinky only. 
**Prev Slide**  (Thumb up) Raise hand above the blue threshold line and extend the Thumb only. 
**Zoom In/Out** (Four fingers up) Move your hand up to zoom in and down to zoom out. 
**Color: Red**  (Thumb + Index) Change drawing color to Red. 
**Color: Green** (Mid + Ring + Pinky) Change drawing color to Green. 
**Color: Blue**  (Ring + Pinky) Change drawing color to Blue. 
**Undo (Erase)** (Index + Mid + Ring) Remove the last drawn line segment. 
**Clear All**  (All fingers up) Wipe all drawings from the current slide. 
**Save Slide**  (Thumb + Index + Mid) Save a screenshot to your Downloads folder. 


## Installation & Setup

### 1. Requirements
* Python 3.x
* Webcam
* Windows OS (for path and fullscreen compatibility)

### 2. Dependencies
Install the required libraries using pip:
pip install opencv-python numpy cvzone mediapipe

### 3. Folder Structure
Ensure your slide images are stored in a folder. Update the 'folderpath' variable in the script to point to your images:
folderpath = r"C:\Users\Path\To\Your\Slides"


## Controls
* 'a' Key: Press 'a' on your keyboard to exit the application.

Developed for Gesture-Based Human Computer Interaction.
README.txt
Displaying README.txt.
