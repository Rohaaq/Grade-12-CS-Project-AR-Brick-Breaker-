# VR Project - Hand-Controlled Environment Explorer

This is my final project for my Grade 12 Computer Science class, exploring virtual reality (VR) and hand-tracking technologies. Being passionate about VR, I aimed to get practical experience by implementing a project using computer vision and hand-tracking libraries to interact with a virtual environment.

The actual project can be tried [here](https://colab.research.google.com/github/Rohaaq/Grade-12-CS-Project-AR-Brick-Breaker-/blob/main/Hand_Tracked_Environment_Explorer_GR12CS_Project.ipynb).

## Project Overview

The project began with a large vision, and I sought to explore how far I could take it with the time and resources I had available. Much of the project was a learning curve—getting acquainted with Google Colab, SDKs, and libraries I hadn't used before. The attached documents (Project Design and Project Requirements) provide further insights into the process and goals. They can be found in the project files.

## Project Design Summary

### Hand-Controlled Environment Explorer

This project focuses on implementing hand tracking as a form of interaction with a virtual environment. Hand tracking refers to tracking the position of a hand virtually, achieved either through outside-in tracking (like sensors in the HTC Vive) or inside-out tracking (such as the camera-based tracking of the Oculus Quest).

Hand tracking is typically powered by computer vision, which enables computers to identify and track objects in images and video. In the context of this project, computer vision is used to track hand movements, which can then be used to manipulate objects or navigate virtual spaces.

### Augmented Reality (AR) and Mixed Reality (MR)

Augmented Reality overlays digital elements onto real-world views, usually with limited interaction. This project takes this concept further by using hand tracking to allow real-time, physical interaction with these elements. In this way, it explores the realm of mixed reality, blending the physical and digital worlds in a more interactive manner.

### How the Project is Being Built

The main goal is to create a computer-vision-based hand tracker to navigate a virtual environment. Initially, this environment will be a simple text-based ASCII maze that can be navigated using hand movements. The project uses Python and relies on libraries such as **MediaPipe** for hand tracking and **OpenCV** for image manipulation.

### Input and Output

- **Input**: Webcam footage or pre-recorded video for hand tracking.
- **Output**: A visual representation of an ASCII-based environment, controlled by hand movements.

### Modules and Development Breakdown

1. **Basic Hand Tracking - Output Movement**:
   - Set up hand tracking using **MediaPipe**.
   - Track the position of the index finger and output movement data (X and Y coordinates).
   - Implement a function to process and display webcam feed.

2. **Constructing the Environment**:
   - Design and display a simple ASCII maze that reacts to hand movements.
   - Global variables will track the position of the hand to move around the environment.

3. **Potential Extensions (Branches)**:
   - Explore animated maps with interaction.
   - Investigate AR-like interactions, where elements overlay real-world views from a camera feed.
   - Consider implementing 3D navigation if feasible, based on z-axis tracking.

### Tools and Libraries

- **Python** (project language)
- **Google Colab** (development environment)
- **MediaPipe** (hand-tracking library)
- **OpenCV** (for image processing)

### References and Resources

The following resources were instrumental in the development of this project:

- [mediapipe_hands.ipynb](https://github.com/google/mediapipe)
- [YOLOv4 Object Detection in Google Colab](https://colab.research.google.com/drive/1xdjyBiY75MAVRSjgmiqI7pbRLn58VrbE?usp=sharing#scrollTo=RPDr23YFW_7c)
- [MediaPipe Hand Tracking Tutorial](https://iqraanwar.medium.com/mediapipe-computer-vision-55821a144f7f)

## Conclusion

This project represents my journey into virtual reality and computer vision. While still a work in progress, it lays the groundwork for future exploration in VR, AR, and possibly mixed reality. With more time, I plan to enhance the virtual environment and improve the accuracy and responsiveness of hand tracking.
