# UniRep: code for embedding and retrieval research

This repository will contain code for reproducing different embedding and retrieval models, such as Dense retriever (on MSMARCO), [Splade](https://github.com/naver/splade) (sparse retriever), [UnifieR](https://arxiv.org/abs/2205.11194) (hybird retriever), and [Udever](https://arxiv.org/abs/2310.08232) (universal embedder for multiple natural and programing languages).

## Udever
[Language Models are Universal Embedders](https://arxiv.org/abs/2310.08232) [Arxiv]

`udever` embedders are finetuned from `bloom` models via BitFit on MS MARCO Passage Ranking, SNLI and MultiNLI data. It is a universal embedding model across tasks, natural and programming languages. (From the technical view, udever is merely with some minor improvements to `sgpt-bloom`)

<img width="338" height="259" src="https://user-images.githubusercontent.com/26690193/277643721-cdb7f227-cae5-40e1-b6e1-a201bde00339.png" />

The **code used to train these checkpoints** can be downloaded at this [Google Drive](https://drive.google.com/file/d/1CI6zbRSKKMRGH2WpSselb68aI9MUwtmF/view?usp=sharing) link.

### Checkpoints / 模型权重

On HuggingFace:
 - [izhx/udever-bloom-560m](https://huggingface.co/izhx/udever-bloom-560m)
 - [izhx/udever-bloom-1b1](https://huggingface.co/izhx/udever-bloom-1b1)
 - [izhx/udever-bloom-3b](https://huggingface.co/izhx/udever-bloom-3b)
 - [izhx/udever-bloom-7b1](https://huggingface.co/izhx/udever-bloom-7b1)

On ModelScope / 魔搭社区:
 - [damo/udever-bloom-560m](https://modelscope.cn/models/damo/udever-bloom-560m)
 - [damo/udever-bloom-1b1](https://modelscope.cn/models/damo/udever-bloom-1b1)
 - [damo/udever-bloom-3b](https://modelscope.cn/models/damo/udever-bloom-3b)
 - [damo/udever-bloom-7b1](https://modelscope.cn/models/damo/udever-bloom-7b1)
