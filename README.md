\# xBD Disaster Building Damage Assessment



A deep learning project for assessing building damage from pre-disaster and post-disaster satellite imagery using the xBD (xView2) dataset.



\## Project Overview



This project explores computer vision techniques for disaster response by identifying building damage following natural disasters.



The project includes two model approaches:



\- \*\*ResNet18:\*\* Building-level damage classification.

\- \*\*Siamese U-Net:\*\* Experimental pixel-level damage segmentation using paired imagery.



\## Damage Categories



\- No Damage

\- Minor Damage

\- Major Damage

\- Destroyed



\## Technologies Used



\- Python

\- PyTorch

\- ResNet18

\- Siamese U-Net

\- OpenCV

\- Pandas

\- NumPy

\- xBD / xView2 dataset

\- Google Colab



\## Model Evaluation



The ResNet18 building classifier achieved the following validation results:



| Metric | Score |

|---|---:|

| Accuracy | 88.29% |

| Macro F1-score | 88.36% |



The Siamese U-Net segmentation branch is experimental. Its per-class IoU and F1 results require careful interpretation, particularly for minor- and major-damage categories.



\## Repository Contents



\- `T229.ipynb` — Jupyter notebook containing the project workflow, experiments, and evaluation.



\## Limitations



\- ResNet18 performs building-level classification on image crops; it does not independently generate pixel-level segmentation masks.

\- Siamese U-Net segmentation performance varies by damage category.

\- Geographic alignment of generated damage outputs requires separate verification.

\- Reported classifier metrics are validation results, not independent test-set results.



\## Purpose



This project was developed as part of an AI/ML internship task to explore deep learning approaches for post-disaster building damage assessment.



\## Disclaimer



This is an experimental project intended for educational and research purposes. Predictions should not be treated as authoritative damage assessments without further validation.

