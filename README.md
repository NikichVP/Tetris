# Gesture-Controlled Tetris

A **Tetris game controlled using hand gestures**, built with **Mediapipe**, **OpenCV**, and **Pygame**.

## Features
- **Hand gesture control**: Move, rotate, and drop Tetriminos using intuitive hand gestures.
- **Interactive visuals**: Finger positions are highlighted on the webcam feed (index finger in red, thumb and middle fingers in green).
- **Dynamic gameplay**: Gestures are processed in real-time for seamless interaction.
- **Scoring system**: Earn points for clearing lines; the game ends when no moves are possible.

## How It Works
The project integrates:
- **Mediapipe Hands**: For tracking finger movements and detecting gestures.
- **Pygame**: For rendering the game grid, Tetriminos, and handling game logic.
- **OpenCV**: To capture webcam video feed for gesture recognition.

### Supported Gestures
- **Move Left**: Swipe your index finger left.
- **Move Right**: Swipe your index finger right.
- **Rotate**: Swap the relative positions of your thumb and middle finger.
- **Drop Tetrimino**: Drag your index finger downward.

## Tests
![photo 1](test1.png)
![photo 2](test2.png)

## Requirements
- Python 3.8 or higher
- Libraries:
  - `pygame`
  - `mediapipe`
  - `opencv-python`

Install the required libraries with:
```bash
pip install pygame mediapipe opencv-python
