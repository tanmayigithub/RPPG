This project provides a comprehensive pipeline for processing electrocardiogram (EKG/ECG) data, focusing on remote photoplethysmography (rPPG) signal extraction, visualization, and basic analysis. It demonstrates loading datasets, preprocessing signals, and visualizing EKG traces, including R-wave detection and labeling.

Installation and Requirements:
Platform : Googlecolab, Jupyter Notebook
Accelerator: GPU
Python Packages Required:
numpy
scipy
pandas
matplotlib
Dataset and Data Loading:
EKG Data - The notebook that uses the scipy.datasets.electrocardiogram by downloading the ecg.dat from the offical source4
The workflow and main functions:
Data Loading: Automated download and parsing via scipy utilities.

Visualization: Plotting EKG signals using matplotlib, including segment and R-wave visualization.

Data Slicing: Allows selection and analysis of short time windows.

Signal Processing: Includes basic filtering, thresholding, and event labeling (e.g., R-peak detection).

Interpretation: Outputs descriptive statistics and graphical summaries for EKG signals.

