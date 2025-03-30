# Self Yoga Pose Correctness Detection

Welcome to **Self Yoga Pose Correctness Detection** – a cutting-edge yoga pose recognition system that leverages machine learning to deliver real-time feedback on your posture! This project is designed to empower yoga practitioners, researchers, and developers to explore and enhance the way we interact with yoga through technology.

## Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Setup Instructions](#setup-instructions)
- [Tech Stack](#tech-stack)
- [My Contributions](#my-contributions)

## Overview

This project uses the **MediaPipe** framework to estimate body poses from live video feeds and processes the extracted coordinates with a **trained logistic regression model** for accurate yoga pose classification. Whether you're a seasoned yogi or just starting out, this system provides actionable feedback to help you improve your posture and practice safely.

## Key Features

- **Real-time Pose Detection:** Capture live video and extract precise body coordinates.
- **Accurate Classification:** Utilizes a logistic regression model trained on a robust dataset of labeled yoga poses.
- **User-Friendly Interface:** Provides a smooth, interactive interface with immediate feedback on pose accuracy.
- **MediaPipe Integration:** Leverages MediaPipe’s powerful pose estimation capabilities for reliable performance.

## Setup Instructions

Follow these steps to run the project locally:

1. **Clone the Repository:**
   
2. **Create a Virtual Environment (Optional but Recommended):**
  python -m venv env
  source env/bin/activate   # For Linux/Mac
  env\Scripts\activate      # For Windows
  
3. **Install Dependencies:**
  pip install -r requirements.txt
  
4. **Run the Application:**
  python main.py
  Ensure your webcam is connected for real-time video feed!

## Tech Stack
-  Python: Core language for machine learning and application logic.

-  MediaPipe: Framework for real-time pose estimation.

-  Logistic Regression: Machine learning model for pose classification.

-  OpenCV: For video processing and interfacing with the webcam.

-  Additional Libraries: NumPy, scikit-learn, and more for data processing and model evaluation.

## My Contributions

In this project, I played a key role in refining the machine learning pipeline and ensuring the system was both efficient and user-friendly. My contributions include:

- **Algorithm Evaluation:**  
  Tested and compared multiple algorithms—including CNN, RNN, and Linear Regression—to determine the best fit for the project. I discovered that Logistic Regression provided the most reliable results with minimal computational overhead, making it ideal for users with lower-specification computers.

- **Data Management & Analysis:**  
  Worked extensively with data preprocessing and analysis to ensure the training datasets were robust and well-curated, enhancing the overall accuracy of pose classification.

- **Documentation & Code Optimization:**  
  Improved the project documentation for clarity and usability, making it easier for other developers and practitioners to understand and contribute. I also optimized the model integration and real-time performance, ensuring a smoother and faster user experience.

- **System Optimization:**  
  Enhanced the real-time feedback mechanism, integrating model updates that boost performance while reducing resource demands.

Together, these efforts have significantly elevated the project's efficiency, accessibility, and overall impact.

