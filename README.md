# **Visual Question Answering with CLIP on VizWiz Dataset**

## 📌 Overview

This project focuses on solving the Visual Question Answering (VQA) task using the VizWiz dataset, which features real-world images taken by visually impaired users alongside spoken questions. Leveraging the power of CLIP (Contrastive Language–Image Pretraining), we extract image and text features and train a classifier to predict the most accurate answer. The model architecture is inspired by recent research that freezes CLIP and only trains lightweight classifier layers, ensuring efficient and scalable performance.

## 📂 Contents

**Jupyter Notebook** – End-to-end implementation: data preprocessing, feature extraction using CLIP, model architecture, training, evaluation, and visualizations.
**Project Report** – A detailed explanation of the task, architecture, training strategy, visualizations, and results.
**Sample Outputs** – Qualitative predictions on unseen test images with model-generated answers.


## ✨ Key Features

**CLIP-based VQA**: Uses pre-trained CLIP for extracting visual and textual features.
**Lightweight Classifier**: Only classifier layers are trained, reducing computational cost.
**Dual-Head Output**: Predicts both the answer and its type.
**Visualization**: Includes accuracy/loss curves and prediction samples.
**Answerability Handling**: Separate classification for "unanswerable" questions.
**Report-Ready**: Well-documented methodology and results in LaTeX-formatted report.

## 📊 Dataset
https://www.kaggle.com/datasets/ingbiodanielh/vizwiz
Purpose: Real-world VQA dataset targeting accessibility applications
Size:
  20,523 training image-question pairs
  4,319 validation samples
  205,230 human-annotated answers

## 📚 References
- Learning Transferable Visual Question Answering System via Frozen CLIP and Synthetic Question Generation
https://arxiv.org/abs/2206.05281
- CLIP: Learning Transferable Visual Models From Natural Language
https://arxiv.org/pdf/2103.00020
