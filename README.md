# Tensorflow Sagemaker sample

This repo stores an example of how to train a tensorflow model and deploy to production using Amazon Sagemaker.

1. Explore and Train.ipynb - loads the dataset, trains a CNN and saves the model
1. sample_utils.py - helper functions used in the notebooks
1. tensorflow_serving_container.ipynb - compresses the saved model, uploads it to s3 and deploys the model
