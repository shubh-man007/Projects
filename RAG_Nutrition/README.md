
## RAG-Nutrition

- This project features a Retrieval-Augmented Generation (RAG) model, based on the `google/gemma-2b-it` language model (**Hugging Face**).

## Model Description

- **Retrieval-Augmented Generation (RAG):** 
    Combines a dense retriever with a powerful generator, enabling the model to fetch relevant information from a document set and generate contextually accurate responses.

- **Retriever:**  Searches through a pre-processed document index to retrieve the most relevant passages, based on user queries. This process helps the model stay grounded in specific knowledge sources and improves the factual accuracy of responses.

- **Generator(google/gemma-2b-it):** A large-scale language model fine-tuned to generate coherent and context-sensitive answers by synthesizing information from retrieved passages.

- **FineTuning Dataset:**  The model has been fine-tuned on the PDF "Human Nutrition: 2020" by the University of Hawaii, a comprehensive document covering essential topics in human nutrition. This specialized dataset allows the model to provide accurate, nutrition-based answers.
## Requirements:

* Install the requirements.
```bash
pip install -r requirements.txt
```
* Run the jupyter notebook, recommended to use a minimum 8GB GPU.
```bash
run model.ipynb
```
## Overview:

![Working](https://github.com/user-attachments/assets/8a84dc24-4408-4e6e-8b2c-753a63cc3196)


## Output:
![output](https://github.com/user-attachments/assets/69bf9126-0e2c-4861-9ca6-383788b1db6a)

* Check the `context.txt` file for context and output generated
