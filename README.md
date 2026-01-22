# RAG with TinyLlama and BAAI retriever 

## Overview

Retrieval-Augmented Generation (RAG) in this repository is build with Llama Index framework.
LLM used is a [TinyLlama/TinyLlama-1.1B-Chat-v1.0](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0).
BAAI retriever is a [BAAI/bge-small-en-v1.5](https://huggingface.co/BAAI/bge-small-en-v1.5).
Vector store is a Chroma

## Installation

```shell
pip install -r requirements.txt
```

## Requirements
* Tensorflow == 2.15.0
* Pytorch == 2.2.1+cu121
* Python >= 3.9
* Transformers >= 4.34.0
* sklearn == 1.6.1


## Usage

For llamaindex1(1).ipynb and finetune_embedding.ipynb I used Google Collab with GPU T4.
Notebook gemma-generation-v2.ipynb was used on kaggle. 

## TODO
Replace model tinyllama to Llama 3.2 1B. Fine tunning retrieval using NT Xent loss with compariment to tfidf as a base model

## Disclaimer
For some reasons github had some problems with llamaindex(1).ipynb outputs so I had to clear them. If you want to see them donwload previous version of llamaindex(1).ipynb localy  
