# HanLP: Han Language Processing

The multilingual NLP library for researchers and companies, built on PyTorch and TensorFlow 2.x, for advancing state-of-the-art deep learning techniques in both academia and industry. HanLP was designed from day one to be efficient, user friendly and extendable. It comes with pretrained models for various human languages including English, Chinese, Japanese and many others.

This tutorial guides you to run the T5-Base model with [this Jupyter notebook](https://github.com/vmware/vSphere-machine-learning-extension/blob/main/examples/model_serving/nlp/hanlp/HanLP.ipynb).

Steps to run the example:

1. Create a new notebook server on **Kubeflow on vSphere** dashboard with 2 CPUs and 4G RAM using custom Docker image `projects.registry.vmware.com/models/notebook/inference:nlp-pytorch-cpu-v3`. GPU is not needed. 

2. `CONNECT` to the notebook server and launch a Terminal in the created notebook server.

3. Download the Jupyter notebook in the Terminal via command: 

   ```shell
   wget https://raw.githubusercontent.com/vmware/vSphere-machine-learning-extension/master/examples/model_serving/nlp/hanlp/HanLP.ipynb
   ```

4. Open the downloaded notebook file follow the steps in the notebook to reproduce the results.
