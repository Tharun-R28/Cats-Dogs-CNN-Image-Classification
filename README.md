# Cats vs Dogs Image Classification using CNN

A deep learning project that classifies images as cats or dogs using a Convolutional Neural Network (CNN) built with PyTorch.

## Project Overview

This project explores binary image classification using deep learning. A CNN learns visual features from labelled cat and dog images and predicts which class an input image belongs to.

The workflow includes dataset loading, image preprocessing, corrupted-image checking, dataset splitting, CNN model development, training, validation, and evaluation.

## Technologies Used

- Python
- PyTorch
- Torchvision
- Pillow
- Matplotlib
- Jupyter Notebook

## Dataset

The project uses a labelled Cats vs Dogs image dataset organised into two classes:

- `Cat`
- `Dog`

The dataset is stored locally and is not included in this repository because of its size.

## Data Preprocessing

- Check for unreadable or corrupted images.
- Resize images to a consistent size of 32 × 32 pixels.
- Convert images into PyTorch tensors.
- Split the dataset into training, validation, and test subsets.

## CNN Architecture

The model uses convolutional layers to extract image features, ReLU activation functions, max pooling to reduce spatial dimensions, and fully connected layers to predict the class.

## Model Training and Evaluation

The model is trained using labelled images and evaluated on a separate test set.

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- Confusion matrix

Actual evaluation results should be added here after successfully running the final test evaluation.

## Project Structure

```text
Cats-Dogs-CNN-Image-Classification/
├── Dog_vs_Cat.ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Clone the repository.
2. Install the required Python libraries.
3. Download the dataset and organise it into `PetImages/Cat` and `PetImages/Dog`.
4. Open the notebook in JupyterLab.
5. Run the notebook cells in order.

### Install Dependencies

```bash
pip install torch torchvision matplotlib pillow jupyter
```

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Cats-Dogs-CNN-Image-Classification.git
```

Replace `YOUR-USERNAME` with your GitHub username.

## Future Improvements

- Experiment with data augmentation.
- Compare different CNN architectures.
- Plot training and validation curves.
- Improve generalisation and test performance.
- Add a simple interface for predicting individual images.

## Author

Tharun R

GitHub: https://github.com/Tharun-R28
