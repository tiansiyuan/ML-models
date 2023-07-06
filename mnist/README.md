This is a simple convolutional neural network in PyTorch and train it to recognize handwritten digits using the MNIST dataset. Training a classifier on the MNIST dataset can be regarded as the hello world of image recognition.

Please refer to:

- mnist.ipynb

It uses PyTorch framework and requires 0.5 CPU/1G RAM, but no GPU.

- MNIST-Tensorboard.ipynb

It uses Tensorflow framework and requires 1 CPU/4G RAM, no GPU.

- pipeline.ipynb

It contains the steps to create the pipeline file, mnist.yaml.

You may have problem pulling gcr.io/ml-pipeline/argoexec:v3.3.8-license-compliance, using the method in https://github.com/xujinheng/imageswap-webhook-proxycache can solve the problem.
