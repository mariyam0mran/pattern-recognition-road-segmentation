# pattern-recognition-road-segmentation
Pattern Recognition segmentation project using classical computer vision methods (OpenCV) and evaluation metrics (e.g., pixel accuracy/IoU).

**Team:** Mariam Raed Yaqoub, Husam Sawaqed (PSUT)

## Overview
This repository contains our Pattern Recognition course project implemented in Python (Jupyter Notebook).
We built and evaluated a computer vision pipeline, including:
- A **classical image-processing approach** (OpenCV-based), and
- A **deep learning approach** (PyTorch).

## What we did
- Data preparation and preprocessing
- Implemented a classical CV pipeline (thresholding / contour logic as needed)
- Implemented a deep learning model in PyTorch (training + evaluation)
- Compared outputs using visual results and evaluation metrics

## Tech Stack
Python, Jupyter Notebook, NumPy, OpenCV, Matplotlib, PyTorch, TorchVision

## Repository Structure
- `notebooks/` → project notebook
- `images/` → result screenshots 
- `requirements.txt` → Python dependencies
## Dataset
This project uses the **Road Lane Segmentation Images and Labels** dataset
from Kaggle:

https://www.kaggle.com/datasets/princekhunt19/road-lane-segmentation-imgs-and-labels

The dataset contains road images and corresponding segmentation masks
for lane detection tasks.


## How to run
1) Create a virtual environment (recommended)
2) Install dependencies:
   ```bash
   pip install -r requirements.txt

## Results
- Deep Learning Average IoU: **0.8657**
- Classical method IoU: **0.047**
- Deep Learning outperformed the classical pipeline on this task.

