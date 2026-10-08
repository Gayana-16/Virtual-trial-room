# 👗 Virtual Trial Room

A computer vision-based virtual trial room that allows users to visualize clothing items on themselves using webcam input and image processing techniques.

## 📌 Project Overview

The Virtual Trial Room is a web-based application designed to provide a virtual clothing try-on experience.

Users can select clothing items from a digital wardrobe and use a webcam to capture their image. The system detects the user's face or upper body using the Haar Cascade algorithm and overlays the selected clothing item onto the user's image.

The project aims to bridge the gap between traditional shopping and online shopping by providing an interactive virtual trial experience.

## ✨ Features

- 👕 Select clothing items from a digital wardrobe
- 📷 Capture user input using a webcam
- 🧑 Face/upper-body detection using Haar Cascade
- 🖼️ Resize and overlay clothing images
- 🌐 Web-based interface
- ⚡ Real-time image processing
- 🛍️ Virtual clothing try-on experience

## 🛠️ Technologies Used

- Python
- Flask
- OpenCV
- NumPy
- HTML
- CSS
- JavaScript
- Haar Cascade

## 🔄 How It Works

1. User selects an outfit from the wardrobe.
2. The application receives an image through the webcam.
3. The Haar Cascade algorithm detects the user's face or upper body.
4. The selected clothing image is resized according to the detected region.
5. The clothing image is overlaid onto the user's image.
6. The final virtual try-on result is displayed.

## 📂 Project Structure

```text
virtual-trial-room/
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── models/
│   └── haarcascade_frontalface_default.xml
│
├── static/
│   └── assets/
│
├── templates/
│   ├── index.html
│   ├── shirt.html
│   └── pant.html
│
└── docs/
    └── Virtual_Trial_Room_Presentation.pptx
