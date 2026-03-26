# Understanding Attention Mechanisms: Improving Sequence Learning in Neural Networks

This repository contains the code and tutorial for an experiment exploring how attention mechanisms improve sequence modelling in neural networks. The project compares a baseline Recurrent Neural Network (RNN) with an attention-enhanced RNN using the IMDB movie review dataset for binary sentiment classification.

The objective of this tutorial is to demonstrate how neural networks process sequential text data and how attention mechanisms allow models to focus on the most informative parts of an input sequence. The notebook implements both models, trains them on the dataset, and evaluates their performance using validation loss, validation accuracy, and attention visualisations.

To run the experiment, install the required Python libraries:

pip install torch numpy pandas matplotlib scikit-learn datasets

After installing the dependencies, open the Jupyter notebook:

jupyter notebook 24169372_ml.ipynb

Running the notebook will reproduce the data preprocessing steps, model training process, evaluation results, and attention weight visualisations discussed in the tutorial.
