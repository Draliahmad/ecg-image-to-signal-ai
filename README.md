# ECG Image-to-Signal AI 🫀📈

## Overview
This project presents an AI-driven pipeline to convert **ECG images (scanned, photographed, or printed)** into **digital time-series signals**, enabling legacy ECG records to be integrated into modern data-driven cardiology workflows.

## Problem Statement
A large proportion of historical ECG data exists only as paper printouts or image files, making it inaccessible for:
- Automated diagnosis
- Machine learning models
- Longitudinal cardiac monitoring

This project bridges that gap by reconstructing digital ECG signals from images.

## Methodology
1. **Image Preprocessing**
   - Grayscale conversion
   - Noise removal
   - Gridline suppression

2. **Signal Extraction**
   - Edge detection
   - Pixel-to-amplitude mapping
   - Time-axis reconstruction

3. **Post-processing**
   - Smoothing & normalization
   - Error correction
   - Signal validation
## Figures

### Figure 1 — ECG Overlay
![ECG Overlay](assets/Figure_1_ECG_Overlay.png)

### Figure 2 — Error Distribution
![Error Distribution](assets/Figure_2_Error_Distribution.png)

### Figure 3 — Correlation Heatmap
![Correlation Heatmap](assets/Figure_3_Correlation_Heatmap.png)

### Figure 4 — Mean Absolute Error per Lead
![MAE Bar Chart](assets/Figure_4_MAE_BarChart.png)

### Figure 5 — Image-to-Signal Conversion Pipeline
![Image to Signal](assets/Figure_5_Image_to_Signal_Conversion.png)

## Results
- Accurate ECG waveform reconstruction
- Low reconstruction error
- High correlation with reference signals

## Repository Structure
assets/ # Figures and visual results
presentation/ # Final PDF and PPTX presentation

## Applications
- Digitization of paper ECG archives
- AI-assisted cardiology diagnostics
- Clinical decision support systems
- Retrospective medical data analysis
- Wearable ECG reconstruction

## Tech Stack
- Python
- OpenCV
- NumPy
- SciPy
- Matplotlib
- Signal Processing
## Presentation
The full project presentation is available in the `presentation/` folder:
- PDF (final slides)
- PowerPoint version
## Author
**Dr. Ali Ahmad**  
MBBS | MSc Clinical & Molecular Microbiology | MSc Drug Discovery & Development  
GitHub: https://github.com/Draliahmad
