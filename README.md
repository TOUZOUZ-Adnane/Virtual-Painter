# Virtual Painter

## Description

The Virtual Painter application allows users to draw on a digital canvas using hand gestures detected via a webcam. It supports changing brush colors and using an eraser with simple hand movements. The application uses MediaPipe for hand tracking and OpenCV for rendering the virtual canvas and interacting with it.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TOUZOUZ-Adnane/Virtual-Painter.git
2. Navigate into the project directory:
   ```bash
   cd Virtual-Painter
3. Create a virtual environment:
   ```bash
   python -m venv venv
4. Activate the virtual environment:
- On Windows:
   ```bash
   venv\Scripts\activate
- On macOS/Linux:
   ```bash
   source venv/bin/activate
5. Install the required Python libraries:
   ```bash
   pip install opencv-python mediapipe


## Usage

1. **Ensure that your webcam is properly connected.**

2. **Prepare a folder named `assets` with overlay images for brush colors and the eraser.**

3. **Run the application:**

   ```bash
   python virtual_painter.py
4. Use the following hand gestures to interact with the application:

- Color Selection:

  - **Move your hand with two fingers up** to select a color or the eraser from the top bar.
  - Colors and eraser are selected based on the position of your hand.

- Drawing:

  - **Point with your index finger up** to draw.
  - The drawing color can be changed by selecting different colors from the top bar.

- Erasing:

  - **Point with your index finger up and move your hand** to erase the drawing.

- Clear Canvas:

  - **Move your hand to the left side of the top bar** to clear the canvas.

## Directory Structure

- `main.py`: Main application script.
- `assets/`: Folder to store overlay images for colors and the eraser.

## Code Overview

- **Hand Tracking:** Uses MediaPipe to track hand landmarks and determine gestures.
- **Drawing:** Renders the drawing based on hand gestures and selected color.
- **Color and Eraser Management:** Allows changing the drawing color or using the eraser.

## Troubleshooting

- Ensure that your webcam is properly connected and accessible.
- Verify that all dependencies are correctly installed.
- Make sure the `assets` folder contains the necessary images for colors and the eraser.

## Contact

For any issues or questions, please contact me via:

- Email: [adnane.touzouz.ta@gmail.com](mailto:adnane.touzouz.ta@gmail.com)
- LinkedIn: [Adnane Touzouz](https://www.linkedin.com/in/adnane-touzouz/)
   
