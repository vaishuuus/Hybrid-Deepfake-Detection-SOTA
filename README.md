# Hybrid-Deepfake-Detection-SOTA
Official implementation of “Deepfake Image Forensics through a Hybrid Model of Error Level and Frequency Analysis with CNNs”

## Key Results
- **Accuracy:** 96.61%
- **AUC:** 0.9942
- **F1-Score:** 0.9662

## Model Architecture
Our model uses a dual-branch fusion strategy:
1. **Visual Stream:** EfficientNet-B0 backbone.
2. **Forensic Stream:** ELA and DCT feature extraction.
3. **Attention Mechanism:** Weighted feature fusion for robust detection.

##  How to Run
Open the provided `.ipynb` file in Google Colab, upload your dataset, and run all cells.
