# Task-2: Sentinel2 Images Feature Matching

# Kaggle notebook link
[UA Deforestation | Feature Matching](https://www.kaggle.com/code/artemzysko/ua-deforestation-feature-matching)

# Dataset
[Deforestation in Ukraine from Sentinel2 data](https://www.kaggle.com/datasets/isaienkov/deforestation-in-ukraine/data)

# Requirements
pip install -r "task-2/requirements.txt"

# Overview
This project focuses on the analysis of satellite images to identify and compare specific geographical features.

# What I did?
- Feature Detection & Matching:
Applied SIFT to extract and match keypoints between Sentinel-2 images, enabling comparison of geographical features across seasons.

- Image Preprocessing:
Implemented functions for loading, resizing, and normalizing high-resolution Sentinel-2 images. Images were normalized to 0-255 range.

- Lazy Image Loader:
Built a lazy loader to load images on demand with optional resizing, enhancing efficiency for large datasets.

- Custom Matcher:
Created a feature matching class that identifies and filters good matches, with visualization of matched features using.

- Notebook Documentation:
Documented the workflow in a Jupyter Notebook, covering preprocessing, feature matching, and result visualization for tracking seasonal land changes.

