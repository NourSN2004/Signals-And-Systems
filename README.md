# Signals-And-Systems
# MATLAB Fourier Analysis and Signal Processing

This repository contains the MATLAB code and analysis conducted for the **EECE 340: Signals and Systems** course project at the **American University of Beirut**. The project focuses on **Fourier Analysis** and its applications in signal representation, transformation, and reconstruction, with real-world scenarios such as seismic activity and sound wave analysis.

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Key Features](#key-features)  
3. [Files and Structure](#files-and-structure)  
4. [Methodology](#methodology)  
5. [Results](#results)  
6. [Usage Instructions](#usage-instructions)  
7. [Acknowledgments](#acknowledgments)

---

## Project Overview

The project explores the use of **Fourier Analysis** in representing, transforming, and reconstructing signals. Key objectives include:
- Investigating the effects of varying Fourier coefficients and signal periods.
- Applying Fourier Transform (FT) and Inverse Fourier Transform (IFT) to analyze and reconstruct signals.
- Exploring real-world applications, such as seismic activity caused by elephants and sudden sound waves.

---

## Key Features

- **Fourier Series Approximation**: Representation of time-limited signals using Fourier series for varying numbers of coefficients (`n`) and periods (`T`).
- **Signal Transformation**: Application of FT and IFT to transform between time and frequency domains.
- **Real-World Applications**:
  - Analysis and reconstruction of seismic signals (e.g., elephant activity).
  - Sudden sound wave (e.g., thud) processing and visualization.
- **Error Analysis**: Evaluation of square errors and Root Mean Square Error (RMSE) for signal reconstruction accuracy.

---

## Files and Structure

The repository includes the following files:

1. **`main.m`**: Main script demonstrating signal representation, Fourier Transform, and reconstruction for all cases.
2. **`ft.m`**: Function to compute the Fourier Transform of a time-domain signal.
3. **`ift.m`**: Function to compute the Inverse Fourier Transform to reconstruct signals.
4. **`sample.m`**: Function to sample a continuous signal at specified rates.
5. **`reconstruct.m`**: Function to reconstruct signals from sampled data using sinc interpolation.
6. **`real-signal.txt`**: Simulated seismic signal data for analysis.
7. **`elephant-signals.txt`**: Simulated seismic signals caused by elephants for analysis.

---

## Methodology

### 1. Fourier Series Representation
- Investigated the effects of varying the number of Fourier coefficients (`n`) and signal periods (`T`) on the accuracy of signal approximation.
- Analyzed the trade-off between computational complexity and representation accuracy.

### 2. Fourier Transform and Inverse Transform
- Applied Fourier Transform to visualize the frequency-domain representation of signals.
- Used Inverse Fourier Transform to reconstruct signals from their frequency-domain representations.

### 3. Sampling and Reconstruction
- Sampled signals at different rates (`fs1`, `fs2`, `fs3`) to analyze the effects of undersampling and oversampling.
- Reconstructed signals using sinc interpolation and evaluated reconstruction errors.

### 4. Real-World Applications
- **Seismic Signals**: Analyzed combined seismic signals caused by elephants, demonstrating the use of Fourier analysis for real-world events.
- **Sudden Sound Waves**: Processed and visualized sound wave data to highlight the flexibility of Fourier methods.

---

## Results

- **Fourier Series Representation**:
  - Increasing the number of coefficients (`n`) improved accuracy, with diminishing returns beyond a certain threshold.
  - Larger signal periods (`T`) captured broader signal features but introduced oversampling complexities.

- **Signal Transformation**:
  - Demonstrated the duality between rectangular pulses in the time domain and sinc functions in the frequency domain.
  - Validated the reconstruction of signals using IFT with low reconstruction error.

- **Real-World Signal Analysis**:
  - Successfully transformed and reconstructed seismic signals caused by elephants and sudden sound waves.
  - Quantified reconstruction errors, showcasing the accuracy of Fourier analysis.

---

## Contributors

- **Nour Shammaa**  
- **Nour Fawaz**

---

## Acknowledgments

This project was developed as part of the **EECE 340: Signals and Systems** course under the guidance of **Prof. Hadi Sarieddine** at the **American University of Beirut**.

Feel free to enhance or extend this project with additional signal processing techniques or real-world applications. If you encounter issues or have suggestions, please open an issue or submit a pull request.

