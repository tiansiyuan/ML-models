# PSLA: Improving Audio Tagging with Pretraining, Sampling, Labeling, and Aggregation

PSLA is a strong training pipeline that can significantly improve the performance of all models we evaluated (by 24.2% on average) on AudioSet and FSD50K. By applying PSLA on a CNN+Attention model, the author achieved new state-of-the-art results on both AudioSet and FSD50 while the model only has approximately 16% parameters compared with the previous state-of-the-art model ([PANNs](https://arxiv.org/abs/1912.10211)) in early 2021. The model is still the best CNN based model now.

Please refer to PSLA.ipynb which is based on https://github.com/YuanGongND/psla/blob/main/README.md, which is BSD 3-Clause License.

It requires 4 CPUs/16G RAM/1 GPU.
