# Pikachu Detector

This repo contains code for a quick project I did on training a neural detection model for detecting the Pokemon Pikachu.

## Installation

The Pikachu Detector has been tested using Python `3.11`.
If you are able to get this running on an older version of Python, or the Pikachu Detector fails to run on a later version, please open an issue and I will look into it.

You can set up your Python envrionment using any method (e.g., Poetry, pipenv, conda, etc.), but please make sure you have **all** packages from `requirements.txt` installed. 

**NOTE**: I have tested this with `poetry` and included the relevant `poetry` files.
If you have success with other methods, please let me know and I can add instructions here!

## Dataset

The Pikachu detection dataset can be found on [Kaggle](https://www.kaggle.com/datasets/ainverse/pikachu-detection/data).
It contains 900 images with Pikachu randomly placed into it.
All images can be found in the `images/` directory and bounding boxes for the Pikachu can be found in `annotations.json`.

## Script

The main script for training the detector can be found in `pikachu_detector.ipynb`.