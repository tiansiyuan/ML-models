# MPT-7B

MPT-7B is a decoder-style transformer pretrained from scratch on 1T tokens of English text and code. This model was trained by [MosaicML](https://www.mosaicml.com/).

MPT-7B is part of the family of MosaicPretrainedTransformer (MPT) models, which use a modified transformer architecture optimized for efficient training and inference.

These architectural changes include performance-optimized layer implementations and the elimination of context length limits by replacing positional embeddings with Attention with Linear Biases (ALiBi). Thanks to these modifications, MPT models can be trained with high throughput efficiency and stable convergence. MPT models can also be served efficiently with both standard HuggingFace pipelines and NVIDIA's [FasterTransformer](https://github.com/NVIDIA/FasterTransformer).

This model uses the MosaicML LLM codebase, which can be found in the [llm-foundry repository](https://github.com/mosaicml/llm-foundry). It was trained by MosaicML’s NLP team on the [MosaicML platform](https://www.mosaicml.com/training) for LLM pretraining, finetuning, and inference.

Please refer to MPT-7B.ipynb, which is from https://github.com/mosaicml/llm-foundry/blob/main/TUTORIAL.md, with Apache License 2.0.

It requires 4 CPUs/24G RAM/1 GPU.
