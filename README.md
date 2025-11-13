# Neural-Language-Model-Training-IIIT-assignment2-
# Neural Language Model Training - Assignment 2

## Overview
This project implements a neural language model trained from scratch using PyTorch on the "Pride and Prejudice" dataset by Jane Austen. The purpose is to study sequence modeling and analyze effects of model size on overfitting and underfitting.

## Dataset
- Downloaded from Project Gutenberg.
- Preprocessing includes tokenization and batching.

## Model Architecture
- LSTM-based recurrent neural network.
- Configurable embedding size, hidden state size, and number of layers.
- Dropout regularization employed.

## Training
- Training done using CrossEntropyLoss and Adam optimizer.
- Early stopping based on validation loss to prevent overfitting.
- Three model configurations tested:
  - Small model (underfitting),
  - Large model (potential overfitting),
  - Medium model (balanced fit).

## Results
- Training and validation loss curves plotted.
- Evaluated using prediction difficulty (exponential of loss, akin to perplexity).
- Best model balanced training and validation loss, demonstrating suitable model capacity.

## Usage

### To run training:
1. Open `IIIT_assignment2.ipynb` in Google Colab.
2. Run cells sequentially.
3. Model checkpoints and logs saved in the Colab environment or Google Drive.

### To generate text from trained model:
After training, run the provided generation function in the notebook with a starting prompt.

## Software and Dependencies
- Python 3.8+
- PyTorch
- NumPy
- Matplotlib
- Google Colab for GPU acceleration (optional but recommended)

## Repository Structure

Please contact V John Joe || v.john@op.ittg.ac.in for any questions regarding this project.




