**Air Canvas - Hand Gesture Drawing Application**

Air Canvas is an interactive computer vision application that lets you draw on the screen using only your hand gestures. 
It uses **MediaPipe** for real-time hand tracking and **OpenCV** for drawing, allowing you to create art in the air using your index finger—no touchscreen or mouse needed!

---

## 🎯 Features

- 🎨 Draw with your index finger in real-time
- 🖐️ Switch between 5 colors using gesture-based selection
- 🧼 Clear the canvas instantly with a simple gesture
- 👆 Interactive color palette and UI controls
- 🖼️ Real-time webcam feedback with gesture overlays
- ⚡ Lightweight and runs on most systems with a webcam

---

## 🛠️ Requirements
Install the required Python libraries with:
```
pip install -r requirements.txt
```

## 🚀 How to Run
<p>1.Ensure your webcam is connected.<br>
2.Run the Python script:
```
python air_canvas.py
```<br>
3.Allow access to your webcam if prompted.<br>
4.Use gestures to draw and interact!</p>

## ✋ Gesture Controls
Gesture	Action
☝️ Index finger up	                  Start drawing
✌️ Index + Middle fingers up	        Select color / Clear
✋ Hover over "CLEAR" box	            Clear the canvas
👉 Hover over a color box	            Change brush color
⌨️ Press q key	                      Quit the application

## 🎨 Color Palette
The top bar displays these color options:
🔵 BLUE
🟢 GREEN
🔴 RED
🟡 YELLOW

## 📁 File Structure
air_canvas.py — Main Python script
requirements.txt — List of Python dependencies
README.md — This documentation

## ❗ Troubleshooting
Make sure your webcam is properly connected.
Run the app in a well-lit environment for better gesture detection.
If you encounter errors, try updating opencv-python or mediapipe.

# 📜 License
This project is free to use for personal, educational, and non-commercial purposes.

# 🙏 Acknowledgements
MediaPipe by Google
OpenCV
