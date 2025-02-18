# Virtual Mouse Using Computer Vision

## Project Overview

This project implements a **computer vision-based virtual mouse** using Python. By utilizing **OpenCV**, **pynput**, and **MediaPipe**, the system captures real-time video input from a webcam, detects hand gestures, and maps them to mouse actions such as clicking, scrolling, and cursor movement.

## Features

- **Hand Gesture Recognition:** Uses OpenCV and MediaPipe to detect hand gestures.
- **Mouse Control:** Simulates left-click, right-click, and scrolling using gestures.
- **GUI for Settings:** Provides an interface for adjusting sensitivity.
- **Optimized Performance:** Uses real-time processing techniques to ensure smooth interaction.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Virtual_Mouse_DIP.git
   cd Virtual_Mouse_DIP
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the virtual mouse program**:
   ```bash
   python virtual_mouse.py
   ```

## Dependencies

The following Python libraries are required:

- `opencv-python`
- `pynput`
- `wxPython`
- `mediapipe`

Install them using:

```bash
pip install opencv-python pynput wxPython mediapipe
```

## Usage

- Run `virtual_mouse.py` to start the program.
- Position your hand in front of the camera.
- Use predefined gestures for mouse actions:
  - **Move Cursor**: Move your hand.
  - **Left Click**: Pinch index finger and thumb together.
  - **Right Click**: Pinch middle finger and thumb.
  - **Scroll**: Move hand up/down.

## System Architecture

The system consists of:

1. **Video Input Module**: Captures frames from the webcam.
2. **Image Processing Module**: Detects hand gestures using OpenCV.
3. **Gesture Recognition Module**: Interprets gestures.
4. **Mouse Control Module**: Maps gestures to mouse actions.
5. **User Interface Module**: Provides settings for customization.



## Future Improvements

- Implement multi-hand tracking.
- Add voice control integration.
- Improve gesture accuracy using AI models.

## Contributors

- Diva Merja
- Makadia Yakshkumar Vijaykumar
- Krishna Wadhwani

## License

This project is licensed under the MIT License.

---

Thank you for exploring this project! 🎯

