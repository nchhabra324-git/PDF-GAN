# PDF-GAN

This project implements a **Generative Adversarial Network (GAN)** to model and learn **Probability Density Functions (PDFs)** using **PyTorch**.  
The complete workflow is demonstrated in a Jupyter Notebook.

The objective is to train a generator that can approximate a target probability distribution through adversarial learning.

---

## Features

- GAN implementation using PyTorch
- Generator and Discriminator neural networks
- Learning probability density functions
- Custom data transformations
- Training loop with loss tracking
- Visualization using Matplotlib and Seaborn

---

## Concept Overview

The project focuses on modeling probability distributions using GANs:

- **Generator (G)**: Learns to generate samples resembling the target PDF  
- **Discriminator (D)**: Learns to distinguish real samples from generated ones  
- Both networks improve through adversarial training until the generated distribution approximates the real one

A transformation of the form: z = T_r(x) = x + a_r sin(b_r x) is used to generate or manipulate data distributions during experimentation.

---

## Requirements

Ensure the following dependencies are installed:

- Python 3.8+
- Jupyter Notebook / JupyterLab
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Seaborn

Install dependencies using: pip install torch numpy pandas matplotlib seaborn

---

## How to Run

1. Clone or download the repository  
2. Open the Jupyter notebook: PDF-GAN.ipynb
3. Run all cells sequentially to:
- Generate training data
- Train the GAN
- Visualize generated vs real distributions

---

## Outputs

- Generator and Discriminator loss curves
- Comparison plots of real and generated PDFs
- Insights into GAN convergence behavior

---

## Notes

- This is an experimental and educational project
- GAN training may be unstable depending on initialization
- Results may vary across runs







