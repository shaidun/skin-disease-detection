# Automated Skin Disease Detection Using Deep Learning

## About the Project

This is my undergraduate Final Year Design Project (FYDP) for my BSc in Computer Science and Engineering. In this project, I explored how deep learning can be used to classify skin diseases from clinical images.

I worked with different pretrained CNN models and tried several image preprocessing techniques to understand how they affect the classification results. This repository contains the notebooks and experiments I worked on during the project.

## Experiments

The main experiments included:

- ResNet50V2 model training and five-fold cross-validation
- Hyperparameter tuning with ResNet50V2
- Comparing experiments with and without Gaussian Blur
- Experiments with DenseNet169 and MobileNetV2
- Image preprocessing using OpenCV
- Grad-CAM to visualize the image regions influencing model predictions
- A notebook for testing image-level predictions

## Technologies Used

- Python
- TensorFlow and Keras
- OpenCV
- NumPy and Pandas
- Matplotlib
- Scikit-learn
- Google Colab and Jupyter Notebook

## Dataset

The project uses a 12-class skin disease image dataset. The dataset is not included in this repository.

To run the notebooks, you need to obtain the dataset from its authorized source and update the file paths according to your own Google Drive or local environment.

## How to Run

1. Download or clone this repository.
2. Open the notebooks in Google Colab or Jupyter Notebook.
3. Set up the required Python libraries.
4. Obtain the dataset and update the paths in the notebooks.
5. Run the notebook cells in order.

Some notebooks may require a GPU and adjustments to library versions or file paths.

## Results

I experimented with different models, preprocessing techniques, and training settings. The results varied between experiments, and I learned about the challenges of improving model performance and evaluating deep learning models.

The recorded experimental metrics are available in `results/EXPERIMENT_RESULTS.md`. Since the experiments may use different settings or data splits, their results should not be treated as a direct comparison without further verification.

## What I Learned

Through this project, I gained practical experience with image preprocessing, transfer learning, model training, hyperparameter tuning, cross-validation, model evaluation, and Grad-CAM explainability.

I also learned that building a useful model requires more than achieving a high accuracy score. Proper evaluation and understanding the model's limitations are important parts of the process.

## Project Status

This project is an academic research prototype and has not been published as a research paper. It has not been clinically validated and should not be used for medical diagnosis or treatment decisions.

I am sharing this repository to document my work, experiments, and learning throughout my final-year project.