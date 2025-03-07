# Image-Preprocessing

# **Image Preprocessing for Machine Learning**

This project demonstrates how to preprocess images for machine learning tasks using Python. It resizes, normalizes, and converts images into tensors, making them suitable for input into machine learning models. The preprocessed images are saved and displayed for verification.

---

## Table of Contents
1. [Setup Instructions](#setup-instructions)
2. [Approach](#approach)
3. [Challenges and Assumptions](#challenges-and-assumptions)
4. [Preprocessed Images](#preprocessed-images)
5. [How to Run](#how-to-run)
6. [Showcase Preprocessed Images](#showcase-preprocessed-images)

---

## Setup Instructions

1. Install the required libraries:
   ```bash
   pip install pillow torchvision matplotlib
   ```

2. Place your input images (e.g., `Sample1.png`, `Sample2.png`) in the working directory.

---

## Approach

- The script uses `torchvision.transforms` to preprocess images.
- Each image is:
  - Resized to **224x224 pixels**.
  - Converted to a tensor.
  - Normalized using mean and standard deviation values for RGB images.
- Preprocessed images are saved and displayed for verification.

---

## Challenges and Assumptions

### Challenges
- Image Size: Resizing images to a fixed size may distort their aspect ratio.
- Normalization: The normalization values used are standard for pre-trained models but may need adjustment for custom datasets.

### Assumptions
- Input images are in a common format (e.g., PNG or JPEG).
- The preprocessing pipeline is designed for RGB images.


## Preprocessed Images

- Preprocessed images are saved with filenames like `preprocessed_Sample1.png` and `preprocessed_Sample2.png`.
- The script displays the preprocessed images using `matplotlib`.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install the required libraries:
   ```bash
   pip install pillow torchvision matplotlib
   ```

3. Place your input images (e.g., `Sample1.png`, `Sample2.png`) in the working directory.

4. Run the script:
   ```bash
   python preprocess_images.py
   ```

5. Check the working directory for the preprocessed images.

---

## Showcase Preprocessed Images

Here are examples of preprocessed images:

### Original Images
1. ![image](https://github.com/user-attachments/assets/c9ef34a7-1144-4400-82c5-b1cea04f4094)
2. ![image](https://github.com/user-attachments/assets/08de9444-c680-4551-86fa-45d10aa1298e)


### Preprocessed Images
![image](https://github.com/user-attachments/assets/38fbec59-6c30-4822-b41c-bc2f2bea289b)
