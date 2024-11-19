
## Nutri-RAG

- This project features a Retrieval-Augmented Generation (RAG) model, based on the `google/gemma-8b-it` language model (**Hugging Face**).

## Model Description

- **Retrieval-Augmented Generation (RAG):** 
    Combines a dense retriever with a powerful generator, enabling the model to fetch relevant information from a document set and generate contextually accurate responses.

- **Retriever:**  Searches through a pre-processed document index to retrieve the most relevant passages, based on user queries. This process helps the model stay grounded in specific knowledge sources and improves the factual accuracy of responses.

- **Generator(google/gemma-8b-it):** A large-scale language model fine-tuned to generate coherent and context-sensitive answers by synthesizing information from retrieved passages.

- **FineTuning Dataset:**  The model has been fine-tuned on the PDF "Human Nutrition: 2020" by the University of Hawaii, a comprehensive document covering essential topics in human nutrition. This specialized dataset allows the model to provide accurate, nutrition-based answers.
## How to Run

* Install the requirements.
```bash
pip install -r requirements.txt
```
* Run the jupyter notebook, recommended to use a GPU.
```bash
run model.ipynb
```
## Overview

![Working](https://github.com/user-attachments/assets/8a84dc24-4408-4e6e-8b2c-753a63cc3196)


## Output
* After running the notebook, a **Gradio** interface link is generated which can be used to enter a query and generate an output.
* The interface is laced with sliders and buttons to customize parameters such as temperature, number of tokens and output format.
* Check the `context.txt` file for context and output generated.
  
https://github.com/user-attachments/assets/cb22d01a-c71d-4c6d-b20e-7a23e1e1468b
