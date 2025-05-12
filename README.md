#  Deep Learning Multimodal System for Rare Neurological Disorder Detection

This repository documents the development of a deep learning-based multimodal diagnostic system that integrates MRI imaging and genomic data to enable early detection of rare neurological disorders.

##  Objective

To design and implement an AI system that leverages both medical imaging and genomic insights for accurate and early-stage detection of rare neurological diseases.

##  Project Components

- **MRI Preprocessing**: Handling and visualizing NIfTI (.nii) files.
- **Genomic Data Parsing**: Reading and structuring VCF/FASTA files.
- **Model Architecture**: Dual-input deep learning (CNN for MRI + DNN for Genomic).
- **Multimodal Fusion**: Integration of features from both modalities.
- **Evaluation**: ROC, AUC, accuracy, and visualization (e.g., Grad-CAM).
- **Reporting**: Weekly progress, visualizations, and final documentation.

##  Repository Structure

```
├── data/                # Sample and preprocessed data
├── notebooks/           # Jupyter notebooks for exploration and development
├── models/              # Saved models and architectures
├── src/                 # Source code for training, preprocessing, etc.
├── reports/             # Progress logs, evaluation reports, visualizations
├── docs/                # Learning logs and references
├── requirements.txt     # Dependencies
└── README.md            # This file
```

##  Weekly Progress

Check the `reports/weekly_progress.md` for detailed week-by-week updates.

##  Sample Modalities

- MRI: NIfTI format (3D brain scans)
- Genomics: VCF/FASTA files (variants or raw sequences)

##  Tools & Libraries

- TensorFlow / PyTorch
- NiBabel, scikit-learn, Pandas, NumPy
- Biopython, Matplotlib, SHAP, Captum

##  Learning Logs

All learnings and tutorials will be documented under `docs/`.

