## Rice Image Classification using CNN (PyTorch)

- Implementation of Convolutional Neural Networks (CNNs).
- Classifies rice images into five distinct varieties: Arborio, Basmati, Ipsala, Jasmine, and Karacadag.
- Achieves over 90% accuracy.

## Dataset Details
- **Total Images:** 75,000
- **Classes:** 5 Rice Varieties
- **Dataset Split:**
  - **Training Set:** 60,000 images
  - **Validation Set:** 10,000 images
  - **Testing Set:** 5,000 images

## Requirements
- Python 3.8+
- PyTorch
- torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Installation
- Clone the repository:
  ```bash
  git clone https://github.com/saeedsahar/cnn-model.git
  cd cnn-model
  ```
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```

## Usage
- Run Jupyter notebook for model training and evaluation:
  ```bash
  jupyter notebook cnn-rice-image-classification.ipynb
  ```
- Ensure dataset folder structure matches requirements.

## Model Summary
- **CNN Architecture:** Convolutional layers, pooling layers, batch normalization, fully connected layers.
- **Optimizer:** Adam
- **Loss Function:** Cross-Entropy Loss

## Results
- **Training Accuracy:** 92.8%
- **Validation Accuracy:** 91.2%
- **Training Loss:** 0.36
- **Validation Loss:** 0.32

## Evaluation Metrics
- High precision, recall, and F1-score.
- Strong ROC-AUC performance.

## Accessibility
- Visualizations optimized for color-blindness and visual impairments.

## License
- Licensed under MIT License (see `LICENSE` file).

## Contact
- Saher Saeed: saeedsahar@gmail.com

- Enjoy exploring CNN-based image classification!

