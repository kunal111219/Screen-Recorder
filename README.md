# Screen Recording Project

## Overview

This project captures your screen and records it into a video file using Python. It utilizes the `pyautogui` library for taking screenshots and `cv2` (OpenCV) for video processing. The recorded video is saved in MP4 format.

## Features

- Records the entire screen at a specified resolution.
- Customizable frame rate for recording.
- Real-time display of the recording window.
- Stop recording with a key press.

## Requirements

- Python 3.x
- `pyautogui` library
- `opencv-python` library
- `numpy` library

## Installation

1. **Install Dependencies**

- You can install the required libraries using pip:

    ```bash
    pip install pyautogui opencv-python numpy

## Usage

1. **Clone the Repository**

    ```bash
    git clone https://github.com/username/Screen-Recorder.git
    cd Screen-Recorder

2. **Run the script**

    Execute the script to start recording:

    ```bash
    python Screen_recording.ipynb

3. **Stop the script**

    Press the q key to stop the recording and save the video.

## Configuration

- Resolution: The default resolution is set to 1920x1080. You can modify the resolution variable in the script if you need a different resolution.
- Frame Rate: The default frame rate is set to 60.0 FPS. Adjust the fps variable to change the recording frame rate.
- Video Codec: The script uses the XVID codec for encoding. If needed, you can change the codec in the cv2.VideoWriter_fourcc() function.

## Contributing

- Feel free to contribute to this project by submitting issues or pull requests. For major changes, please open an issue first to discuss what you want to change.

## Contact

- For any questions or feedback, please reach out to <rastogikunal19@gmail.com>.
