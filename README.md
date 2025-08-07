# Age Prediction from Facial Images

This project implements a Convolutional Neural Network (CNN) to predict the age of individuals from facial images. The codebase follows a modular structure with separate files for training, testing, and utility functions.

## Technologies
- Python
- PyTorch
- torchvision
- Weights & Biases (wandb) for experiment tracking
- ONNX (for model export)

## Project Structure
- `main.py`: Main execution file that sets up and runs the full training and evaluation pipeline.
- `train.py`: Functions to train the model.
- `test.py`: Functions to test and evaluate the trained model.
- `prueba.py`: Additional testing and model export utilities.
- `test_trained_model.ipynb`: Jupyter notebook for testing and analysis of a trained model.

## How to Run
1. Clone the repository.
2. Install the required libraries:
3. Run the main script:
4. (Optional) Track training metrics and visualize results using Weights & Biases (wandb).

## Notes
- The project includes ONNX export capabilities for model portability.
- Experiment tracking is integrated using wandb; make sure to have an active account or configure a local run.

## Contributors
Francisco Carcaño, [UAB Computational Mathematics and Data Analytics program].
