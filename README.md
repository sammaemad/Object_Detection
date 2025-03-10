# Object Tracking Application

This application tracks moving objects in a video using OpenCV and Streamlit. It uses the MOG2 background subtractor to detect moving objects and draw a green rectangle around them.

## Features

- Upload a video file in MP4, AVI, MOV, or WMV format.
- Track moving objects in the video.
- Draw green rectangles around detected moving objects.

## Requirements

- Python 3.x
- Streamlit
- OpenCV
- NumPy

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Object_Detection.git
    cd Object_Detection
    ```

2. Install the required packages:
    ```sh
    pip install streamlit opencv-python-headless numpy
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. This app is deployed on streamlit cloud.

3. Upload a video file and watch the application track moving objects in real-time.

## File Structure

- `app.py`: Main application file.
- `.gitattributes`: Git configuration file for handling line endings.

## License

This project is licensed under the MIT License.
