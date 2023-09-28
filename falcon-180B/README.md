# Falcon 180B

Falcon 180B is a super-powerful language model with 180 billion parameters, trained on 3.5 trillion tokens. It's currently at the top of the Hugging Face Leaderboard for pre-trained Open Large Language Models and is available for both research and commercial use..

This model performs exceptionally well in various tasks like reasoning, coding, proficiency, and knowledge tests, even beating competitors like Meta's LLaMA 2.

Among closed source models, it ranks just behind OpenAI's GPT 4, and performs on par with Google's PaLM 2 Large, which powers Bard, despite being half the size of the model. 

[tiiuae/falcon-180B](https://huggingface.co/tiiuae/falcon-180B)

It is a Gated model. You need to be granted access to this model.

In the terminal, run the following commands:

```shell
export HTTP_PROXY='http://proxy.vmware.com:3128'
export HTTPS_PROXY='http://proxy.vmware.com:3128'

pip install transformers accelerate

huggingface-cli login
```

Paste token generated from https://huggingface.co/settings/tokens and press Enter.

