# Gesture Control Assistant

Welcome to the Gesture Control Assistant! This project allows you to control your computer using hand gestures detected via your webcam. It leverages computer vision and machine learning to recognize hand gestures and map them to mouse and system control actions, such as moving the cursor, clicking, scrolling, and adjusting volume or brightness.

## Features

- **Hand Gesture Recognition:** Uses your webcam to detect and interpret hand gestures in real time.
- **Virtual Mouse Control:** Move the mouse, left/right/double click, and drag & drop using gestures.
- **Scrolling:** Scroll vertically and horizontally with pinch gestures.
- **System Volume & Brightness Control:** Adjust system volume and screen brightness with specific gestures.
- **No Extra Hardware Needed:** Only a webcam is required.

## Requirements

- Windows OS
- Python 3.6–3.8.5
- Webcam

## Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd Gesture_control_assistant-main
   ```

2. **(Recommended) Create a virtual environment:**
   ```bash
   python -m venv myenv
   myenv\Scripts\activate  # On Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Install additional system packages if needed:**
   - For audio and brightness control, you may need:
     ```bash
     pip install pycaw screen_brightness_control
     ```

## Usage

1. **Navigate to the `src` directory:**
   ```bash
   cd src
   ```

2. **Run the gesture controller:**
   ```bash
   python Gesture_Controller.py
   ```

   - The webcam window will open, and you can start using hand gestures to control your system.

3. **(Optional) For voice assistant or other features:**
   - If you have a voice assistant script (e.g., `Proton.py`), run it as needed.

## How It Works

- The system uses MediaPipe for hand tracking and gesture recognition.
- Gestures are mapped to actions such as mouse movement, clicks, scrolling, and system controls.
- The code is modular and can be extended for more gestures or actions.

## Notes

- This project is optimized for Windows.
- Make sure your webcam is connected and accessible.
- Some features (like brightness control) may require administrator privileges.

## BY Anshika Rawat :) 
star if it helped
