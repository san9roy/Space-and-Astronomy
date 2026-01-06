# Space-and-Astronomy
Demonstrates FFT-Based 1-D Signal and Image Processing for Scientific Noise Reduction.

**Project Overview**

This project demonstrates the application of Fourier-based signal and image processing techniques to improve data quality in scientific measurements. Using Python, I apply Fast Fourier Transform (FFT) methods to both time-domain signals and 2D astronomical images in order to analyze, interpret, and suppress noise.

The goal is not classification or machine learning, but understanding data at a physical and instrumental level, as required in physics, space science, and engineering contexts.

**Objectives**

Analyze noisy scientific data in both time/space domain and frequency domain

Apply FFT-based filtering techniques for noise reduction

Perform image stacking to improve signal-to-noise ratio (SNR)

Interpret noise and filtering from a physical perspective

**Tools and Libraries**

Python

NumPy

Matplotlib

SciPy (optional)

OpenCV (optional, image handling)

**Part I — Signal Processing (1D FFT Analysis)
Dataset**

A noisy scientific time-series signal is analyzed (simulated or sourced from a real detector dataset). The signal consists of a low-frequency physical component combined with high-frequency noise.

Methodology

Visualize the raw time-domain signal

Apply Fast Fourier Transform (FFT) to move into frequency space

Identify dominant signal frequencies and noise-dominated regions

Apply a frequency-domain filter (low-pass or band-pass)

Reconstruct the filtered signal using inverse FFT

Physical Interpretation

In physical measurement systems, noise often arises from environmental fluctuations, electronic readout, or stochastic processes. These noise sources typically manifest as high-frequency components in the frequency domain. FFT allows clear separation of physically meaningful signal frequencies from noise, enabling targeted filtering without distorting the underlying signal.

**Part II — Image Processing (2D FFT & Image Stacking)
Dataset**

Astronomical images (e.g., star fields, nebulae, telescope images) are used to demonstrate space-relevant image processing techniques.

Image Stacking

Multiple images of the same scene are combined using:

Mean stacking

Median stacking

This reinforces consistent photon signals while averaging out random noise.

Frequency-Domain Image Filtering

Compute the 2D FFT of stacked images

Visualize the spatial frequency spectrum

Apply low-pass or band-pass frequency filtering

Reconstruct the filtered image using inverse FFT

Perform contrast enhancement for visualization

Physical Interpretation

Noise in astronomical imaging arises from photon shot noise, sensor read noise, and atmospheric disturbances. FFT-based filtering suppresses high-frequency spatial noise while preserving large-scale physical structures, improving image clarity and scientific usability.

Why FFT Is Essential in Scientific Data Processing

FFT enables transformation between:

Time ↔ Frequency domains (signals)

Space ↔ Spatial-frequency domains (images)

Many noise sources are difficult to identify in the original domain but become clearly separable in frequency space. This makes FFT a fundamental tool in experimental physics, astrophysics, detector systems, and signal processing.

**Conclusion**

This project demonstrates practical understanding of:

Signal and image processing beyond basic data analysis

Frequency-domain reasoning

Physical interpretation of noise and filtering
