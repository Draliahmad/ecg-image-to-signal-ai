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

## Author
**Dr. Ali Ahmad**  
MBBS | MSc Clinical & Molecular Microbiology | MSc Drug Discovery & Development  
GitHub: https://github.com/Draliahmad
