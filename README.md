# RAG with TinyLlama and BAAI retriever 

## Overview

Retrieval-Augmented Generation (RAG) in this repository is build with Llama Index framework.
LLM used is a [TinyLlama/TinyLlama-1.1B-Chat-v1.0] (https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0).
BAAI retriever is a [BAAI/bge-small-en-v1.5] (https://huggingface.co/BAAI/bge-small-en-v1.5) model 

## Installation

```shell
pip install -r requirements.txt
```

## Requirements
* Tensorflow == 2.15.0
* Pytorch == 2.2.1+cu121
* Python >= 3.9
* Transformers >= 4.34.0


## Usage

For llamaindex1(1).ipynb and finetune_embedding.ipynb I used Google Collab with GPU T4.
Notebook gemma-generation-v2.ipynb was used on kaggle. 
