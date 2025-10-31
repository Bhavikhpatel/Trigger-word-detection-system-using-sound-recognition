This project was deployed in huggingface spaces - https://huggingface.co/spaces/bhavikhpatelhf/trigger-word-detector

# Trigger Word Detection System  

A Flask-based web application that detects a **trigger word (wake word)** in an uploaded or recorded audio file. The system preprocesses the input, generates a spectrogram, passes it through a trained deep learning model, and overlays a chime sound whenever the trigger word is detected.

---

## Overview  

This project implements a **real-time trigger word detection system** using deep learning.  
It performs:
1. Audio preprocessing (resampling, trimming/padding, normalization)
2. Spectrogram generation
3. Prediction using a pre-trained model
4. Chime overlay when the wake word is detected
5. Visualization of trigger word detection probability

---

## Features  

- Flask web interface for easy audio upload and prediction  
- Automatic conversion of browser-recorded audio (`.webm`) to `.wav`  
- Audio preprocessing to ensure model compatibility  
- Deep learning–based wake word detection  
- Visualization of prediction probability graph  
- Chime overlay output when the wake word is detected  
- Audio download and playback functionality  

---

## Tech Stack  

**Backend:** Flask, TensorFlow Keras  
**Audio Processing:** PyDub, NumPy, SciPy  
**Visualization:** Matplotlib  
**Frontend:** HTML, CSS, JavaScript
