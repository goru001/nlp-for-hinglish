# NLP for Hinglish (Code mixed Hindi+English)

This repository contains Language model for Code mixed Hinglish (Hindi and English) - spoken in Indian sub-continent.

Methodology followed in this repo is detailed in [this paper](https://arxiv.org/abs/2010.02094), accepted at Dravidian-Codemix-HASOC2020@FIRE2020
 
## Dataset

1. [Synthetically Generated Hinglish Dataset from Wikipedia Articles](https://www.dropbox.com/sh/as5fg8jsrljt6k7/AADnSLlSNJPeAndFycJGurOUa?dl=0)

## Results

### Language Model Perplexity (on validation set)

| Architecture/Dataset | Synthetically Generated Wikipedia Articles Dataset |
|:--------:|:----:|
|   ULMFiT  |  86.48  |

### Visualizations
 
##### Word Embeddings

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection]() |


## Pretrained Models

#### Language Models 
Download pretrained ULMFiT LM from [here](https://www.dropbox.com/sh/2aknrf5b70kbf3l/AABwAkxtcCPKMBBp2BF_JdQca?dl=0)

#### Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://www.dropbox.com/sh/9q08xejeha77sj6/AAAyI8M9yvIqU_exatz36yrJa?dl=0)