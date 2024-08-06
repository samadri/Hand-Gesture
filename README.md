# Hand-Gesture
Hand Gesture Recognition Using Open CV
## Introduction

The hand gesture recognition system uses OpenCV to detect and recognize hand gestures in real-time from video input. This project is useful for implementing gesture-based control systems and enhancing human-computer interaction.

## Features

- Real-time hand detection using video input.
- Gesture recognition based on predefined patterns.
- Two versions of the script (`write.py` and `write.v2.py`) with different functionalities and improvements.
- Modular codebase with utilities for common tasks.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/hand-gesture-recognition.git
    ```
2. Navigate to the project directory:
    ```bash
    cd hand-gesture-recognition
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Ensure that your system has a working webcam or video input device.

## Usage

### Basic Usage

1. Run the main script to start the hand gesture recognition system:
    ```bash
    python write.py
    ```
2. The script will start capturing video input from your webcam. Hand gestures will be detected and recognized in real-time.

### Using `write.py`

- This script is the base version of the hand gesture recognition system.
- It detects hand gestures and classifies them based on the predefined logic in the script.

To run `write.py`:
```bash
python write.py
Using write.v2.py
write.v2.py is an enhanced version of the original script with improved accuracy and additional features.
It includes better preprocessing of the input, more robust gesture recognition logic, and additional functionalities.
To run write.v2.py:

bash
Copy code
python write.v2.py
Technologies Used
Python: The primary programming language used.
OpenCV: For real-time computer vision and image processing.
NumPy: For numerical operations and array handling.
Utils Module: A collection of utility functions used across the project.

### Project Structure

plaintext
Copy code
|-- utils/
|   |-- __init__.py
|   |-- helper_functions.py
|-- write.py
|-- write.v2.py
|-- requirements.txt
|-- README.md
