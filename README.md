# RoPE-PyTorch
PyTorch Implementation of RoPE (Rotary Positional Embeddings) from the RoFormer Paper (Su et al. 2021).

RoPE, that combines the absolute and the relative approaches to encode positional information of the tokens in the transformer architecture, is used in many recent developments like LlaMA and PaLM, and is shown to outperform (or perform at par with) all other position encoding techniques available currently.

I recently did a deep dive into the Positional Encoding Space (wrote very brief notes [here](https://www.linkedin.com/feed/update/urn:li:activity:7107913352038821889/), [here]()) and RoPE clearly stood out because of its clever approach that combines the simplicity of implementing Absolute PEs with the performance benefits given by Relative PEs. The Math is beautiful (it always is), and so I am doing a PyTorch implementation of RoPE in this repository for ML developers who like scripts better than equations to understand it.

[Blog](https://srishti-git1110.github.io/RoPE/) coming out soon!

Resources -
* [RoFormer](https://arxiv.org/abs/2104.09864)
* [Eleuther AI's Blog](https://blog.eleuther.ai/rotary-embeddings/)
