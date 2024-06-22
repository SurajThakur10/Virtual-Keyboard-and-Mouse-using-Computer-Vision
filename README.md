
# Virtual Keyboard and Mouse using Computer Vision


![App Screenshot](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*-wc57H4KMXJXZpeze0eVSQ.gif)

## Overview

The Virtual Keyboard and Mouse using Computer Vision is an AI-based system designed to replace traditional mouse and keyboard tasks with virtual equivalents. Leveraging real-time camera input and computer vision technologies like image segmentation and gesture recognition, this project demonstrates how to control mouse functions and display a virtual keyboard for user interaction.


## Features

- Virtual Mouse: Uses real-time camera input to detect hand gestures, controlling mouse functions like clicking and scrolling through image segmentation and gesture recognition. The system mimics the functionalities of a traditional mouse.
- Virtual Keyboard: Displays a virtual keyboard on the screen, allowing users to select characters by positioning their fingers inside designated rectangles, as detected by a webcam.


## Technologies Used

- **MediaPipe:** An open-source framework by Google used for building machine learning pipelines. It provides tools for cross-platform development and performance evaluation, crucial for real-time hand gesture detection and tracking.
- **OpenCV:** Essential for image processing tasks, including object detection and real-time video processing. OpenCV facilitates the detection and manipulation of objects within images and video streams.
- **TensorFlow:** Employed for training models to recognize sign language gestures. TensorFlow supports transfer learning and real-time detection, enhancing the system's capability to interpret signs accurately.


## System Requirements
**Software**
- Operating System: Windows 7 or above / Linux
- Programming Language: Python and its libraries (OpenCV, NumPy, MediaPipe, TensorFlow)

**Hardware**
- Computer: Desktop or Laptop with minimum 3GB RAM and any integrated processor
- Webcam: For continuous image capture and processing



## Installation
**Clone the Repository:**
```bash
  git clone https://github.com/SurajThakur10/Virtual-Keyboard-and-Mouse-using-Computer-Vision.git
```

**Install Dependencies:**
```bash
  pip install -r requirements.txt
```

**Run the Application:**
```bash
  python AiVirtualMouseProject.py
```

```bash
  python virtual keyboard.py
```

## Implementation Details
**Hand Gesture Detection and Tracking**

- Real-Time Video Input: Utilizes webcam to capture video feed, converting it into images for processing.
- Landmark Detection: Detects hand landmarks using MediaPipe, tracking movements to control mouse cursor and clicks.

**Virtual Keyboard Interaction**

- Key Selection: Users interact with an on-screen keyboard by placing their fingers within designated areas, detected by the webcam.
- Adaptation: The interface adapts key size and centroid distance based on user interaction for a user-friendly experience.

## Future Scope
- **Refinement and Optimization:** Further development to enhance system accuracy and performance.
- **Integration with Real-Time Data:** Explore real-time data integration for dynamic gesture recognition.
- **Expanded Accessibility:** Improve accessibility features for users with disabilities, ensuring broader usability.

## Conclusion

**The Virtual Keyboard and Mouse using Computer Vision project demonstrates a novel approach to human-computer interaction, providing a contactless interface that can replace traditional input devices. This system offers significant potential for accessibility and ease of use, particularly benefiting individuals with disabilities.**

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/SurajThakur10/Virtual-Keyboard-and-Mouse-using-Computer-Vision/blob/master/LICENSE) file for details.



