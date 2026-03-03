# OpenCV Full Tutorial with Python

This repository contains the code and resources I have developed while following the [OpenCV Course - Full Tutorial with Python](https://www.youtube.com/watch?v=oXlwWbU8l2o) by freeCodeCamp.

## 🛠️ Setup & Installation

Ensure you have Python installed (version 3.7+ is recommended). Install the necessary libraries via your terminal:

```bash
pip install opencv-contrib-python numpy matplotlib

### Repository Directory Structure

```text
OpenCV-Course-Python/
├── README.md               # Project documentation
├── OpenCV_Basics.md        # Dependencies
├── .gitignore              # Files to ignore (e.g., venv, __pycache__, large data)
├── data/                   # Raw assets
│   ├── photos/             # Image datasets
│   └── videos/             # Video files for processing
├── notebooks/              # Jupyter notebooks for model training
│   └── simpsons_model.ipynb
├── src/                    # Primary source code
│   ├── 01_reading_media.py
│   ├── 02_resizing_rescaling.py
│   ├── 03_drawing_shapes.py
│   ├── 04_basic_functions.py
│   ├── 05_transformations.py
│   ├── 06_contours.py
│   ├── 07_color_spaces.py
│   ├── 08_split_merge.py
│   ├── 09_smoothing_blurring.py
│   ├── 10_bitwise_operators.py
│   ├── 11_masking.py
│   ├── 12_histograms.py
│   ├── 13_thresholding.py
│   ├── 14_gradients_edge_detection.py
│   └── 15_face_detection.py
└── projects/               # Advanced implementations
    ├── face_recognition/
    │   ├── faces_train.py
    │   └── face_recognition.py
    └── deep_learning/
        └── (additional model scripts)
