# Color Detection using Python

## Overview
This project is a simple color detection system using Python, where the user can identify the name of a color by clicking on a specific area in an image. The project uses OpenCV, Pandas, and NumPy libraries to perform the color detection and display the results.

## Features
- **Interactive Color Detection**: Click on any part of the image to get the color name and its RGB values.
- **Color Dataset**: The project uses a pre-defined dataset containing over 800 color names and their corresponding RGB values.
- **Real-time Updates**: The detected color name is displayed on the image as you click on it.

## Technologies Used
- **Python**
- **OpenCV**: For handling image processing tasks.
- **Pandas**: To manage the color dataset efficiently.
- **NumPy**: For numerical operations on arrays.

## Setup and Installation
To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/color-detection.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd color-detection
    ```
3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    Alternatively, install the libraries manually:
    ```bash
    pip install opencv-python pandas numpy
    ```

4. **Run the project:**
    ```bash
    python pr1.py
    ```
    Replace `pr1.py` with the correct script name if necessary.

## How It Works
1. **Load an Image:** The script prompts the user to input the path of the image they want to analyze.
2. **Click to Detect Colors:** The user clicks on any part of the image, and the script identifies the color at that point by comparing it to the dataset.
3. **Display the Results:** The color name and its RGB values are displayed on the image.

## Usage Example
```bash
python pr1.py
