# Transformer-Sentence-Classification
This project aims to develop a Transformer-based model to accurately classify sentences from the PubMed 20k dataset into five categories 'Background', 'Conclusions', 'Methods', 'Objective', 'Results'. This project can make information retrieval and summarization of Biomedical Research more efficient.

## Overview
I utilized TextVectorization, Embeddings, and a Transformer model to categorize sentences into five distinct classes. The model underwent training on the PubMed 20k dataset, achieving a commendable accuracy rate of 70%. Further enhancements in terms of additional training epochs and refined fine-tuning could potentially optimize its performance. This project provided valuable insights into the architecture and workings of the Transformer model. The evaluation of the model encompassed metrics such as F1 score, confusion matrix analysis, and accuracy.

## Results
The model had the best precision and f1 score in the 'METHODS' and 'RESULTS' classes. This indicates that further improvement of the model it can acheive higher accuracy because the sentences are in these two classes. 
Thw worst performance was in the 'OBJECTIVES' class. This is because the sentences in this class are very similar to the 'BACKGROUND' class. 

## Installation
To get started, clone the repository and install the required dependencies:

In Docker and JupyterLab

```bash
git clone https://github.com/lucianoscarpaci/Transformer-Sentence-Classification.git 
```

## License
This project is licensed under the MIT License. 


