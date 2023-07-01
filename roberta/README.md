# RoBERTa

Bidirectional Encoder Representations from Transformers, or BERT, is a revolutionary self-supervised pretraining technique that learns to predict intentionally hidden (masked) sections of text. Crucially, the representations learned by BERT have been shown to generalize well to downstream tasks, and when BERT was first released in 2018 it achieved state-of-the-art results on many NLP benchmark datasets.

RoBERTa builds on BERT’s language masking strategy and modifies key hyperparameters in BERT, including removing BERT’s next-sentence pretraining objective, and training with much larger mini-batches and learning rates. RoBERTa was also trained on an order of magnitude more data than BERT, for a longer amount of time. This allows RoBERTa representations to generalize even better to downstream tasks compared to BERT.

Please refer to:

- RoBERTa.ipynb

It requires 2 CPUs/4G RAM, with 1 or without GPU.
