Nvidia Jetson Live Video Stream Weather Classifier

This is for the iD Tech course Machine Learning with Nvidia Jetson Nano. The main idea is to retrain a reset-18 image classifier neural network to determine the current weather from a live video feed. It has many possible uses, but I was inspired to build it because it could be used to control energy sources for a power grid for emissions reduction given weather conditions.

The Algorithm

This features a network based on resnet-18 that has been retrained to classify a live video feed to detect cloudy, rain, shine, or sunrise weather. It depends on the jetson-inference directory being installed on the Jetson Nano.

This setup includes an Nvidia Jetson Nano and webcam that can classify a live video stream of the sky to classify the weather as cloudy, rain, shine, or sunrise. The dataset of weather images I used from training came from Mendeley Data at https://data.mendeley.com/datasets/4drtyfjtfy/1/files/a03e6097-f7fb-4e1a-9c6a-8923c6a0d3e0

Running this project

1. This project is dependent on an Nvidia Jetson.
2. The jetson-inference library is required to make this install work.

Hardware: This project has been set up on an Nvidia Jetson Nano and a USB webcam. I have used a Logitech C270 720p HD USB webcam. It may also be possible to use a camera with the MIPI-CSI connector rather than USB, however it has not been tested.

This is set up by downloading the dataset, unzipping the dataset, training the model, exporting the model, running the model, and running G Streamer to display the live video feed with the results text overlayed.

This is a link to a video of the setup and demonstration of the project:
https://youtu.be/tv5fM7fUZvg