## Polyp Segmentation in Kvasir Dataset

**This repository implements an AI project for segmenting polyps in colonoscopy images from the Kvasir dataset using deep learning.**

### Project Overview

- Aim: Automatically detect and **segment polyps** in **1000 colonoscopy images** from the Kvasir dataset.
- Key Features:
    - Preprocessing:
        - **Image resizing** for model compatibility.
        - **Data normalization** for improved training stability.
    - Model Architecture:
        - **U-Net model** (PNG visualization provided).
        - Optimized for medical image segmentation.
    - Training Details:
        - Comprehensive **Jupyter notebook** (train.ipynb) guides you through:
            - Data loading and preprocessing.
            - Model training.
            - Performance evaluation.
            - Visualization of results.
    - **Segmentation Masks:**
        - Model predicts pixel-wise masks to accurately identify polyp regions.

### Getting Started

1. **Clone:** `git clone https://github.com/Pooria-Heydarian/Segmentation-Kvasir-SEG`
3. **Download:** Get the Kvasir dataset from [Ksavir-Dataset](https://datasets.simula.no/kvasir-seg/). Place it in the designated directory.
4. **Run:** Open `segmentation.ipynb` in Jupyter Notebook and follow the guide.

### Additional Information

- **U-Net model:** Explore online resources for deeper understanding.
- **Experimentation:** Modify code and adjust hyperparameters for potential performance improvements.

### Contact

- Questions or suggestions? Email: [Pooria_heydarian@gmail.com]

**Disclaimer:**

- This project is for **educational and research purposes only**.
- It is **not intended for medical diagnosis or treatment**.

