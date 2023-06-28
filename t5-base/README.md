With T5 (Text-To-Text Transfer Transformer), we propose reframing all NLP tasks into a unified text-to-text-format where the input and output are always text strings, in contrast to BERT-style models that can only output either a class label or a span of the input. Our text-to-text framework allows us to use the same model, loss function, and hyperparameters on any NLP task.

T5-Base is the checkpoint with 220 million parameters. 

It requires 2 CPUs/4G RAM, but no GPU.
