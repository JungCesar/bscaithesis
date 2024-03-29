# Bsc Artificial Intelligence (UvA) - Julius Bijkerk
Bsc AI Thesis

Thesis topic: Disease Recognition with Deep Learning
This repository contains the code, data, and steps used in my thesis, titled "Investigating Pre-Trained Self-Supervised Deep Learning Models for Disease Recognition"

**Overview**

The goal of this thesis is not only to examine the efficacy of pretrained self-supervised deep learning models like wav2vec in disease recognition from speech analysis, but also to establish a clear and efficient workflow that others can apply to similar disease recognition problems. We also compare the results of wav2vec with traditional machine learning techniques using MFCC features.

The thesis further focuses on understanding, documenting, and conveying each step of the modeling and deployment process comprehensively, intending to create a replicable path for future researchers and developers.

Repository Structure
The repository is organized as follows:

Data: This folder contains the TORGO data files, different versions of the database can be found here: http://www.cs.toronto.edu/~complingweb/data/TORGO/torgo.html, https://www.kaggle.com/datasets/iamhungundji/dysarthria-detection, and https://www.kaggle.com/datasets/pranaykoppula/torgo-audio

The first is used within this thesis for the spectrogram analysis part and the second for the notebooks.

Notebooks: This directory hosts the Jupyter notebooks detailing the analysis, results, and methodology for each step.

The project primarily uses Python and has specific package dependencies. All notebooks can be run online using Google Colab, eliminating the need for a local setup.

Access

Navigate to the notebooks directory.
Open the notebook/model you wish to run.
Select the 'Open in Colab' option.

Usage

All scripts and notebooks are intended to be used within the Google Colab environment. Open the notebook in Colab and follow the instructions in each notebook.

Results

| Model Name    | Accuracy  | Precision | Recall    | F1-Score  | AUC-ROC   |
|---------------|-----------|-----------|-----------|-----------|-----------|
| WAV2VEC 2.0   | 86.25     | 83.49     | 90.55     | 86.87     | -         |
| MFCC + 1D CNN | **90.10** | **85.09** | **97.49** | **90.87** | 90.87     |
| MFCC + MLP    | 83.75     | 78.24     | 93.50     | 85.19     | **93.79** |

Contact

For any queries or feedback, please feel free to reach out to: julius.bijkerk@icloud.com
