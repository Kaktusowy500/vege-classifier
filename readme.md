# Vegetable Classifier Project

This project uses deep learning to classify different types of vegetables. 

## Setup

### Prerequisites

- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) installed on your system.

### Create Conda Environment


1. Create a new conda environment:
    ```bash
    conda create --name vege_env python=3.9.12
    ```

2. Activate the conda environment:
    ```bash
    conda activate vege_env
    ```
3. Set Jupyter notebook to use created enviroment
 
### Install Requirements

1. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
### Run selected notebook
The `vegetable_classification_demo` notebook serves as a demo that loads a pre-trained model and classifies a few example images.

The `vegetable_classification` notebook is a complete project that loads a dataset, explores it, trains a neural network, and analyzes the results.

To train the model yourself using the notebook, you'll need the dataset, which is available [here](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset). It must be unzipped and placed in the `data` directory.