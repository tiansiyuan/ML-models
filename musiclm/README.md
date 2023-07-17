# MusicLM - Pytorch

Implementation of [MusicLM](https://google-research.github.io/seanet/musiclm/examples/), Google's new SOTA model for music generation using attention networks, in Pytorch.

They are basically using text-conditioned [AudioLM](https://google-research.github.io/seanet/musiclm/examples/), but surprisingly with the embeddings from a text-audio contrastive learned model named [MuLan](https://arxiv.org/abs/2208.12415). MuLan is what will be built out in this repository, with AudioLM modified from the other repository to support the music generation needs here.

The notebook, MusicLM.ipynb, is based on the README.md file and https://github.com/lucidrains/audiolm-pytorch/blob/main/audiolm_pytorch_demo.ipynb.

MIT License

It requires 4 CPUs/16G RAM, with or without GPU.
