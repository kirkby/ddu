# Mobile Phone Detector

This project is a mobile phone detector using a webcam and a pre-trained YOLOv8 model. It also includes a Flask server to update and fetch the detection status.

## Requirements

- Python 3.8+
- Flask
- OpenCV
- NumPy
- Ultralytics
- Requests
- Torch

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/mobile-phone-detector.git
    cd mobile-phone-detector
    ```

or simply download the files from the repo and place them in your project.


2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    # or
    python3 - pip install -r requirements.txt
    ```


## Usage

### Running the Flask Server

1. Navigate to the project directory:

    ```bash
    cd /Users/mkm/code/demo
    ```

2. Start the Flask server:

    ```bash
    python server.py
    ```

### Running the Webcam Detector

1. Ensure the Flask server is running.
2. In a new terminal, navigate to the project directory:

    ```bash
    cd /Users/mkm/code/demo
    ```

3. Run the webcam detector script:

    ```bash
    python webcam.py
    ```

### Setting Status via Script

You can set the status using the [set-status.py](http://_vscodecontentref_/0) script:

```bash
python set-status.py