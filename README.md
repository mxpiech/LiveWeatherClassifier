# Nvidia Jetson Live Video Stream Weather Classifier

 This setup includes an Nvidia Jetson Nano and webcam that can classify a live video stream of the sky to classify the weather as cloudy, rain, shine, or sunrise. The dataset of weather images I used from training came from Mendeley Data.

![add image descrition here](direct image link here)

## The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

This features a network based on resnet-18 that has been retrained to classify a live video feed to detect cloudy, rain, shine, or sunrise weather. It depends on the jetson-inference directory being installed on the Jetson Nano.

## Running this project

1. Add steps for running this project.
2. Make sure to include any required libraries that need to be installed for your project to run.

Hardware: This project has been set up on an Nvidia Jetson Nano and a USB webcam. I have used a Logitech C270 720p HD USB webcam. It may also be possible to use a camera with the MIPI-CSI connector rather than USB, however it has not been tested.

[View a video explanation here](video link)
