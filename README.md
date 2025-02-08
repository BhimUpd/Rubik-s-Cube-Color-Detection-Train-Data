# Color Dataset Collection App

This is a Java-based Android application developed using Android Studio and OpenCV for image processing. The purpose of this app is to collect color data to build a dataset for training a model for Rubik's Cube color detection.

## Features

- Captures the mean color of a small rectangular area in the center of the camera preview.
- Stores the RGB values along with a user-defined color name in a CSV file.
- Users can collect and manage multiple data entries.
- Simple interface to view selected data and delete all collected data.
- Allows users to send the CSV file via Gmail with a single button click, where the file is pre-selected as an attachment.

<img src="AppPreview/1" alt="App Screenshot" width="300">



## Usage

1. Open the app and ensure the camera is properly aligned with the color sample.
2. The app will automatically capture the mean RGB color within the center rectangle.
3. Assign a color name and save the entry.
4. View or delete collected data as needed.
5. When ready, press the send button to open Gmail with the CSV file attached.
6. Press send to share the dataset for Rubik's Cube color detection training.

## Purpose

This app is designed to facilitate the collection of color data to improve the accuracy of a Rubik's Cube color detection model. By collecting diverse color samples from different lighting conditions and cube variations, the dataset will help refine the model's performance.

## Contribution

Users are encouraged to collect and send as much data as possible to aid in building a robust dataset. Your contributions will enhance the precision and reliability of the Rubik's Cube color detection system.

## Dependencies

- Android Studio
- Java
- OpenCV

Thank you for contributing to this project!



