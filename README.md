# Deepfake-detection

Deepfake Detection Using Image Processing Techniques

This project presents a lightweight approach to detect deepfake images using classical image processing techniques like frequency domain analysis and face landmark detection. It aims to raise awareness about deepfakes and provide insights into how image processing methods can help identify manipulated content.

Table of Contents

Introduction

Objectives

Methodology

Dataset

Image Processing Techniques

Results

Conclusion

References


🔍 Introduction

Deepfakes are synthetic media generated using deep learning models, where a person's face in an image or video is swapped or manipulated. While deep learning models are effective in creating them, they leave behind subtle artifacts which can be detected through image processing.

🎯 Objective

To analyze and identify deepfake images using simple yet effective image processing techniques without using complex machine learning or deep learning models.

🧪 Methodology

1. Collect real and fake face images.


2. Apply frequency domain analysis to detect abnormal pixel patterns.


3. Use facial landmark detection to analyze asymmetry and unnatural features.


4. Compare results visually between real and fake images.



📁 Dataset

Source: 140k Real and Fake Faces - Kaggle

Description: 70,000 real faces and 70,000 fake faces generated using StyleGAN.


🧠 Image Processing Techniques Used

1. Frequency Domain Analysis:

Applied Fast Fourier Transform (FFT) to analyze noise and frequency artifacts in fake images.



2. Face Landmark Detection:

Used Dlib’s 68-point facial landmark detector to examine eye spacing, jawline symmetry, and mouth position.

Observed minor distortions and irregularities in fake images.




📊 Results

Fake images showed high-frequency noise patterns not visible in real images.

Landmark-based analysis revealed inconsistencies in facial structure in many deepfakes.

Visual inspection supports the hypothesis that classical techniques can distinguish deepfakes to a reasonable extent.


✅ Conclusion

Even without deep learning, deepfakes can be analyzed using classical image processing methods. This project demonstrates the value of understanding frequency and spatial distortions in image-based deepfake detection.

🔗 References

Deepfake Detection Challenge - Kaggle

140k Real and Fake Faces

Dlib facial landmarks: https://github.com/davisking/dlib



---

