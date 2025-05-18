# DLAssignment2

# Variational Autoencoder on QuickDraw Dataset

This project implements a **Variational Autoencoder (VAE)** using TensorFlow/Keras. It is designed to encode and reconstruct 28x28 grayscale images from a subset of the QuickDraw dataset. The project includes:

- A GRU-based encoder for sequence input,
- A convolutional decoder for image reconstruction,
- Latent space visualization with t-SNE,
- Evaluation and visualization of generated samples.

##  Requirements

Install the dependencies using pip:

```bash
pip install numpy matplotlib tensorflow
```


##  How to Run

Open the notebook `ass2.ipynb` in Jupyter Notebook or JupyterLab and run all cells step-by-step. It covers:

1. Data loading and preprocessing
2. Model architecture (encoder and decoder)
3. Training the VAE
4. Sampling from the latent space
5. Visualizing the results using t-SNE

##  Architecture Overview

- **Encoder**: Uses GRU layers to compress 28x28 images into latent vectors.
- **Latent space**: Samples from learned distribution using the reparameterization trick.
- **Decoder**: A convolutional network reconstructs the original image.

##  Output

- Reconstructed images
- t-SNE projection of latent space
- Image generation from sampled latent vectors
