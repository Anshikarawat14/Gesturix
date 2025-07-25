

# Gesture Controlled Virtual Mouse &nbsp;[![](https://img.shields.io/badge/python-3.8.5-blue.svg)](https://www.python.org/downloads/) [![platform](https://img.shields.io/badge/platform-windows-green.svg)](https://github.com/xenon-19/Gesture_Controller)

Welcome to my Gesture Controlled Virtual Mouse project! This tool transforms the way you interact with your computer by letting you control your mouse and perform various actions using just your hand gestures and voice commands. No need for extra hardware—just your webcam and microphone are enough. The system uses advanced machine learning and computer vision techniques to recognize your gestures and voice, making everyday computer tasks more intuitive and touch-free.

With this project, you can move your cursor, click, scroll, drag and drop, adjust volume and brightness, and even use a built-in voice assistant for tasks like searching Google, navigating files, and more. Whether you want to boost productivity, improve accessibility, or just try something cool, this project is designed to be easy to use and fun to explore.

_Note: This project is optimized for Windows and Python 3.8.5._

# Features

### Gesture Recognition
- **Neutral Gesture:** Instantly stop or pause gesture recognition with an open palm.
- **Move Cursor:** Move your hand to control the mouse pointer naturally and smoothly.
- **Left/Right/Double Click:** Perform mouse clicks with simple, distinct hand gestures.
- **Scrolling:** Scroll vertically or horizontally by pinching and moving your hand.
- **Drag and Drop:** Pick up and move files or items with a dedicated gesture.
- **Multiple Item Selection:** Select several items at once using a special gesture.
- **Volume & Brightness Control:** Adjust system volume or screen brightness dynamically with pinch gestures.



# Getting Started

### Prerequisites
- Python 3.6–3.8.5
- Anaconda (recommended for easy environment management)

### Setup Instructions
```bash
git clone https://github.com/xenon-19/Gesture-Controlled-Virtual-Mouse.git
```
1. Create a new environment:
```bash
conda create --name gest python=3.8.5
```
2. Activate the environment:
```bash
conda activate gest
```
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Install additional packages:
```bash
conda install PyAudio
conda install pywin32
```
5. Change directory to the src folder:
```
cd path/to/Gesture-Controlled-Virtual-Mouse/src
```
6. To run the Voice Assistant:
```bash
python Proton.py
```
(Enable gesture recognition by saying "Proton Launch Gesture Recognition")

Or, to run only gesture recognition:
- Uncomment the last two lines in `Gesture_Controller.py`
```bash
python Gesture_Controller.py
```


# License
This project is open source and free to use for personal and educational purposes.
  
