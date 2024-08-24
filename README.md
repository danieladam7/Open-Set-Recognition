# Open Set Recognition Model



This project involves the development of an Open Set Recognition (OSR) model combining a Convolutional Neural Network (CNN) for digit classification with an Autoencoder (AE) for detecting Out-of-Distribution (OOD) samples.
The model effectively distinguishes known classes from the MNIST dataset and unknown samples, leveraging reconstruction error from the Autoencoder to identify unfamiliar inputs.

## Tech Stack 💻
[![My Skills](https://skillicons.dev/icons?i=py,pytorch,tensorflow,)](https://skillicons.dev)

- Programming Languages & Development: Python, PyTorch

- Tools & Technologies: CNN, Autoencoder, Data Augmentation, Thresholding, TSNE, PCA


## Features 🏆
- Open Set Recognition: The model classifies known samples with a baseline CNN and identifies unknown samples using an Autoencoder based on reconstruction error.

- Data Augmentation: Techniques like random horizontal flipping and rotation improve the model's robustness and generalization to unseen data.


## Deployment 🌐
- Training & Evaluation: The model was trained on the MNIST data set and evaluated on a combined data set of MNIST and CIFRA-10 (data the OSR model wasn't trained on), utilizing thresholding based on softmax probabilities and reconstruction errors to balance accuracy for known and unknown classes.

- Visualization Tools: TSNE and PCA were used to visualize the clustering of known and unknown classes, demonstrating the model’s effectiveness.

## Preview 🎞️

![image](https://github.com/user-attachments/assets/1de2ab4e-e5bf-4d26-8dd2-fead805710a3)


## Usage 🎯
- To use this model, follow the provided Jupyter notebooks for training and evaluating the model on your dataset. The notebooks guide through the data preparation, model training, and evaluation processes, including visualization and analysis of results.


## Connect me 📫
[![text](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-adam-backend-developer/)
[![Website](https://img.shields.io/badge/Website-grey?style=for-the-badge&url=https%3A%2F%2FMyWebsite)](https://danieladam.click/)
[![text](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:danielyosef.adam@gmail.com)

