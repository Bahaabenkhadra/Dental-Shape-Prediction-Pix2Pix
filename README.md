# Dental Shape & Aesthetic Prediction via Pix2Pix cGAN

An AI-powered pipeline designed to predict and visualize post-operative dental shapes and aesthetic enhancements for patients prior to undergoing dental procedures. This repository contains the core training workflows and backend architecture used to generate image-to-image translations of dental structures.

# Project Overview
- *Objective:* Map pre-operative dental imagery to highly realistic post-operative clinical outcomes.
- *Model Architecture:* Conditional Generative Adversarial Network (cGAN) based on the *Pix2Pix* framework.
- *Core Stack:* Python, PyTorch, Jupyter Notebook, OpenCV.

# Repository Structure
- `src/server.ipynb`: Main Jupyter Notebook covering data preprocessing, cGAN training loops, inference pipelines, and API server initiation.
- `assets/`: Contains UI screenshots, mobile application mockups, and visual performance results.

# Model & Training Details
- *Generator (`net_G.pth`):* Trained to translate initial dental/jaw alignments into optimized aesthetic smile structures.
- *Discriminator (`net_D.pth`):* Optimized concurrently to distinguish between actual post-op medical results and AI-generated predictions, driving the generator toward pixel-level accuracy.
- *Data Engineering:* Handled specialized image alignment, normalization, and heavy data augmentation to maximize structural fidelity and reduce anatomical bias.

#  How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Bahaabenkhadra/Dental-Shape-Prediction-Pix2Pix.git](https://github.com/Bahaabenkhadra/Dental-Shape-Prediction-Pix2Pix.git)
