## Chatur-GPT

- This project is an implementation of the **`Attention is all you Need`** paper.

## Model Description

- **Transformer Based (124M):** 
    Chatur-GPT is a Generative Pre-Trained model built from scratch which is trained on a multilingual dataset, enabling effective translation across various languages.

- **Visualization:**  Added an **attention visualizer** to dynamically  display the attention patterns of the pre-trained model, providing insights into how the model interprets and prioritizes different parts of input sequences.

- **Dataset:** The model has been trained on **`Opus Books`** a Multilingual dataset imported from HuggingFace. [![Link](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=000)](https://huggingface.co/datasets/Helsinki-NLP/opus_books)

- **Metrics:**  The model has been trained for 20 epochs and the weights have been stored which are later used for inference and visualization. A wordlevel tokenizer has been used for text pre-processing and an input embedding of **`512`** dimensions is used for spatial positioning. The model was able to achieve a **BLEU** score of **`0.68`**, indicating strong translation accuracy and context preservation across languages.
