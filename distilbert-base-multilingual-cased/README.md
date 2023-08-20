This model is a distilled version of the [BERT base multilingual model](https://huggingface.co/bert-base-multilingual-cased). The code for the distillation process can be found [here](https://github.com/huggingface/transformers/tree/main/examples/research_projects/distillation). This model is cased: it does make a difference between english and English.

The model is trained on the concatenation of Wikipedia in 104 different languages listed here. The model has 6 layers, 768 dimension and 12 heads, totalizing 134M parameters (compared to 177M parameters for mBERT-base). On average, this model, referred to as DistilmBERT, is twice as fast as mBERT-base.

This tutorial guides you to run the T5-Base model with [this Jupyter notebook](https://github.com/vmware/vSphere-machine-learning-extension/blob/main/examples/model_serving/nlp/distilbert-base-multilingual-cased/distilbert-base-multilingual-cased.ipynb).

Steps to run the example:

1. Create a new notebook server on **Kubeflow on vSphere** dashboard with 2 CPUs and 4G RAM using custom Docker image `projects.registry.vmware.com/models/notebook/inference:nlp-pytorch-cpu-v3`. All the required Python modules are included in this image. GPU is not needed. 

2. `CONNECT` to the notebook server and launch a Terminal in the created notebook server.

3. Download the Jupyter notebook in the Terminal via command: 

   ```shell
   wget https://raw.githubusercontent.com/vmware/vSphere-machine-learning-extension/master/examples/model_serving/nlp/distilbert-base-multilingual-cased/distilbert-base-multilingual-cased.ipynb
   ```

4. Open the downloaded notebook file follow the steps in the notebook to reproduce the results.
