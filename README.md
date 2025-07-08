# Weapon-detection-system

# 🔫 Weapon Detection System

A real-time weapon detection system using computer vision and machine learning. This project aims to identify weapons in images and video streams, helping to enhance public safety through smart surveillance.

---
## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [License](#license)

## 📖 Overview

This system is designed to detect weapons (like guns or knives) in visual media using deep learning. The model was trained on labeled data and can identify potential threats in real-time from video surveillance.



```bash
python WeaponDetection.py

✅ Features
Real-time weapon detection

Detection from both images and videos

Uses pre-trained deep learning models

Lightweight and easily deployable


🛠 Tech Stack
Python

OpenCV

TensorFlow / Keras

NumPy

scikit-learn

.npy & .pkl model handling

Batch file execution (run.bat)


📁 Project Structure
├── 1.jpg to 9.jpg           # Sample test images
├── WeaponDetection.py       # Main execution file
├── testrain.py              # Training/testing script
├── Y.txt.npy                # Encoded label data
├── history.pckl             # Model training history
├── weapon_testing.cfg       # Config file for testing
├── run.bat                  # Windows batch runner
├── VID-20220405-WA0013.mp4  # Demo video
├── SCREENS.docx             # Project documentation
├── README.md                # Project readme
