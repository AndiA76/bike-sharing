# Bike-Sharing data prediction using MLP and Python

## Overview

This starter project from Udacity's nano-degree course "Deep-Learning" is about building a simple Multi-Layer Perceptron Model to predict daily bike rental ridership. The task is to set up the Neural Network Model (incl. functions to initialize, train and run the model, perform the feedforward and the backpropagation step and update the weights) and using pure Python.

The project is broken down in subtasks starting with loading and preprocessing the data, defining and training the model and finally evaluating the performance of predicting bike rental ridership on a test dataset.

The project is implemented as a Jupyter notebook and can be found there: [Project Notebook](Your_first_neural_network.ipynb)

The neural network model is implemented in a separate Python script: [Python Script](my_answers.py)

## Installation

### 1. Install Python

In order to run the notebook I have used an environment with Python 3.6. For instance, you may want to install [Anaconda](https://docs.anaconda.com/anaconda/install/) with Python 3.6 on your machine.

### 2. Requirements

Further packages that are required to run the notebook are
- jupyter
- numpy
- pandas
- matplotlib

### 3. Download the project from github

You can download the project from github as a zip file to your Downloads folder from where you can unpack and move the files to your local project folder. Or you can clone from Github using the terminal window. Therefore, you need to prior install git on your machine e. g. using

```
conda install -c anaconda git
```

When git is installed you can create your local project version. Therefore, navigate to your project folder and clone the project from github using the command

```
git clone https://github.com/AndiA76/bike-sharing.git
```

Then change to the project directory

```
cd bike-sharing
```

### 4. Bike-sharing data

The datasets used for training, validation and testing the bike-sharing model are provided as *.csv files with the repository in the sub-folder: [Bike-Sharing-Dataset/](Bike-Sharing-Dataset/). You just need to follow the instructions given in the [Project Notebook](Your_first_neural_network.ipynb).

### 5. Run the notebook

Now start a Jupyter notebook to run the project using following command

```
jupyter notebook
```

Navigate to your local project folder in the Jupyter notebook and open [Your_first_neural_network.ipynb](Your_first_neural_network.ipynb) file and run it.
