# Development of an Integrated Computational Pipeline for FTIR Data Analysis

## Overview

This project focuses on developing an automated computational pipeline to process, analyze, and represent Synchrotron-based Fourier Transform Infrared (SR-µFTIR) spectroscopy data. The pipeline incorporates **Singular Value Decomposition (SVD)** for noise reduction and dimensionality reduction, enabling improved analysis of complex biological data.

The pipeline was validated on data studying the postnatal development of the central nervous system (CNS) in mice. It consists of four key modules:
1. **Data Curation**: Quality control to remove low-quality or erroneous data.
2. **Data Preprocessing**: Noise reduction using Savitzky-Golay filters and SVD.
3. **Exploratory Analysis**: Pattern detection via Principal Component Analysis (PCA) and outlier identification.
4. **Statistical Analysis**: Hypothesis testing using ANOVA and visualization of significant findings.

## Key Features

- **Noise Reduction**: Integration of SVD to reduce noise and improve signal clarity in FTIR spectra.
- **Automation**: Modular and customizable design for streamlined and reproducible data analysis.
- **Validation**: Application of the pipeline to CNS developmental studies, demonstrating its effectiveness.

## Results

- Enhanced signal clarity using SVD.
- Efficient processing of SR-µFTIR data.
- Statistical insights into biochemical changes in CNS development.

## Technologies

- **Programming Language**: Python 3.8
- **Libraries**: NumPy, SciPy, Matplotlib, pandas

## Author

This work was conducted by **Juan Torralbo Torrado** as part of the MSc in Bioinformatics at the Universitat Autònoma de Barcelona under the supervision of Dr. Alex Perálvarez-Marín and Dr. Mario López Martín.

---
For more details, refer to the project documentation or contact the author.
