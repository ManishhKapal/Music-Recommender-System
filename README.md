# Sangeet - Facial emotion detection based music recommendation system

### Table of Contents
1. [About the project](#about)
2. [Structure of this repository](#repository-structure)
3. [Future Scope](#future-scope)
4. [References](#references)


### About
This repository demonstrates an end-to-end pipeline for real-time Facial emotion recognition application along with reccommending music based on detected emotions.
Done in three steps:
1. Face Detection: from the video source using OpenCV.
2. Emotion Recognition: using a model trained by using Mediapipe library.
3. Music Recommendation: Using detected emotion to create a search query on Youtube

### Repository Structure
 This repository is organised as:
 - [app](/app.py) This file contain the setup of final web app.
 - [model](/model.h5) This file contains the trained model.
 - [Emotion Detection](./Emotion%20Detection) This folder contains python scripts to train the model.
 - [.streamlit](./.streamlit) This folder contains configuration files for the streamlit theme in Web App.

### Future Scope
- Deploying the Web App.
- Integration of an inbuilt music player using  SpotiPy library, with spotify authentication.
- Addition of more gestures, and control of volume using gesture detection.
- Improved Reliablity and addition of User Feedback 

### References
- [Emotional Detection and Music Recommendation System
based on User Facial Expression - S Metilda Florence and M Uma](https://iopscience.iop.org/article/10.1088/1757-899X/912/6/062007/pdf)


