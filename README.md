# RAG with TinyLlama and BAAI retriever 

## Overview

Retrieval-Augmented Generation (RAG) is the process of optimizing the output of a large language model, 
so it references an authoritative knowledge base outside of its training data sources before 
generating a responseCycles are important for agent-like behaviors, where you call an LLM in a loop,
asking it what action to take next.

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
