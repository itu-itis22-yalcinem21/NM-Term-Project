# Digital Image Watermarking with Custom SVD

This project was developed as a term assignment for the Numerical Methods course at Istanbul Technical University (Spring 2024). It explores robust digital image watermarking using a custom implementation of Singular Value Decomposition (SVD), without relying on external libraries like NumPy for matrix factorization.

## 🧠 Overview
We implemented:
- A QR decomposition-based SVD from scratch
- A watermark embedding & extraction system using that SVD
- Evaluation with PSNR to ensure watermark imperceptibility

## 📁 Files
- `NM_Project3.ipynb`: Main Jupyter notebook containing the implementation and test results.
- `report.pdf`: Project report detailing the methodology, equations, and results.
- `images/`: Sample input and output images used in the experiments.

## 📊 Results
- The watermarking method was tested using standard datasets like *Lena* and *Pepper*.
- Achieved average PSNR > 40 dB under various distortions such as JPEG compression.

## 🚀 How to Run
You can open the notebook using Jupyter:
```bash
jupyter notebook NM_Project3.ipynb
