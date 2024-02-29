# Machine Translation Project - Hindi to English

## Overview

This Machine Translation project aims to translate Hindi text into English using a sequence-to-sequence model with Encoder-Decoder architecture. The model utilizes Long Short-Term Memory (LSTM) units and includes additional dense layers for improved performance.

## Introduction

Machine Translation involves the automatic translation of text from one language to another. This project specifically focuses on translating Hindi text to English using a deep learning approach.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Naveenpoliasetty/Machine-Translation/blob/main/README.md.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```


## Model Architecture

The model employs an Encoder-Decoder architecture with LSTM units. The Encoder processes the input Hindi sequence, and the Decoder generates the corresponding English sequence. Additional dense layers are added to enhance the model's ability to capture complex patterns.

You can refer the paper: https://arxiv.org/abs/2210.11807


## Future Improvements

- Experiment with different architectures (e.g., Transformer models).
- Explore data augmentation techniques for better generalization.
- Fine-tune hyperparameters for improved performance.
