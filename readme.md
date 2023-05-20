# Ai Hand Raise Counter using Pose Estimation

The Ai Hand Raise Counter using Pose Estimation is a computer vision application that uses Mediapipe and OpenCV libraries to detect and count repetitions of a specific exercise based on the user's body movements. It utilizes the Pose estimation model from Mediapipe to track the position of key body landmarks and calculates the angles between relevant body parts to determine exercise repetitions.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed:

- Python (version 3.6 or above)
- OpenCV (cv2)
- Mediapipe
- NumPy

You can install the required libraries using pip:

```bash
pip install opencv-python mediapipe numpy
```

## Getting Started

To get started with the Rep Counter application, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Arunangshu-Das/ai_hand_raise_counter.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ai_hand_raise_counter
   ```

3. Run the script:

   ```bash
   python app.py
   ```

   The application will open a new window displaying the video feed from your webcam with the rep count, left stage, and right stage information.

4. Perform the exercise in front of the webcam and observe the rep count and stage information being updated in real-time.

5. Press 'q' to exit the application.

## How it Works

The application uses the Mediapipe library to detect and track key body landmarks (e.g., shoulders, elbows, wrists) from the video feed captured by the webcam. It then calculates the angles between specific body parts (e.g., shoulder-elbow-wrist angles) to determine exercise repetitions.

The rep count is displayed in the top left corner of the video feed window, while the left stage and right stage information (indicating whether the movement is in the "up" or "down" stage) are displayed in the top middle and top right corners, respectively.

## Customization

You can customize the application according to your specific exercise or requirements. You can modify the angles thresholds to define the "up" and "down" stages of the exercise. Additionally, you can adjust the video feed window size or add visualizations, such as overlays or additional text, to enhance the user experience.

## Demo
[**Project Demo Link**](https://youtu.be/g_flGAyo63E)

## Limitations

Please note that the accuracy and performance of the rep counter may vary depending on various factors, including lighting conditions, camera quality, and the complexity of the exercise. Adjustments and optimizations may be required based on specific use cases and scenarios.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
