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
Figure 1. Overlay comparison between the original reference ECG signal and the reconstructed signal obtained from the ECG image. The close temporal alignment and waveform similarity demonstrate the model’s ability to accurately recover clinically relevant ECG morphology, including QRS complexes and overall rhythm patterns, from image-based inputs.
Key insight:
✔ Visual confirmation that image-to-signal reconstruction preserves ECG shape and timing.
### Figure 2 — Error Distribution
![Error Distribution](assets/Figure_2_Error_Distribution.png)
Figure 2. Distribution of reconstruction errors between the original ECG signal and the image-derived signal across time points. The concentration of errors around low values indicates high reconstruction fidelity, with minimal deviation introduced during the image processing and signal extraction stages.
Key insight:
✔ Most reconstruction errors are small, indicating robust and stable signal recovery.
### Figure 3 — Correlation Heatmap
![Correlation Heatmap](assets/Figure_3_Correlation_Heatmap.png)
Figure 3. Correlation heatmap illustrating the Pearson correlation coefficients between original and reconstructed ECG signals across standard ECG leads. High correlation values across most leads confirm consistent reconstruction performance and preservation of inter-lead relationships critical for clinical interpretation.
Key insight:
✔ Strong lead-wise agreement validates multi-lead ECG reconstruction reliability.
### Figure 4 — Mean Absolute Error per Lead
![MAE Bar Chart](assets/Figure_4_MAE_BarChart.png)
Figure 4. Mean Absolute Error (MAE) values calculated for each ECG lead, quantifying reconstruction accuracy on a per-lead basis. While minor variability is observed between leads, overall low MAE values indicate uniform model performance and absence of lead-specific degradation.
Key insight:
✔ Reconstruction accuracy is stable across all ECG leads.
### Figure 5 — Image-to-Signal Conversion Pipeline
![Image to Signal](assets/Figure_5_Image_to_Signal_Conversion.png)
Figure 5. Overview of the ECG image-to-signal conversion workflow. Raw ECG images undergo preprocessing and trace extraction to isolate waveform information, followed by signal digitization to generate a continuous time-series representation suitable for downstream analysis and machine learning applications.
Key insight:
✔ End-to-end pipeline converts static ECG images into reusable digital signals.
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
