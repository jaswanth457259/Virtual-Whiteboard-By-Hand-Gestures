# Webcam Whiteboard with MediaPipe Hands

This project sets up a simple web application that utilizes MediaPipe's hands model to interact with a whiteboard. The application allows users to draw on a canvas using their hands as input, view webcam feed, and control drawing functions with a user interface.

## Features

- **Webcam Input**: Displays live feed from the user's webcam.
- **Whiteboard Output**: A canvas where users can draw using hand gestures.
- **MediaPipe Hand Detection**: Detects and tracks hand gestures to interact with the whiteboard.
- **Clear Drawing**: A button to clear all drawings on the whiteboard.
- **Toggle Whiteboard**: A button to stop and start the whiteboard functionality.
- **Color Picker**: Allows users to select drawing colors.

## Files

- `index.html`: The main HTML file containing the structure and styles for the application.
- `hands.js`: JavaScript file that initializes MediaPipe Hands and handles the drawing logic.

## Setup

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
