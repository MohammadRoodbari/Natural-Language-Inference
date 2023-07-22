# Natural-Language-Inference
Natural Language Inference on Farstail dataset using hugging face transformers 
> This repository is made for the NLP course project -  2023.
> 
---

## Models
**The First Approach**

Using [ParsBERT](https://huggingface.co/HooshvareLab/bert-base-parsbert-uncased) as a Embedding Layer for Feed Forward Neural Network
### Results
|    Train Acc.   |   Train loss.   |   Test Acc.   |
| :-------------: | :-------------: | :-----------: |
|      0.813      |      0.175      |      0.83     |

**The Second Approach**

Fine-tuning [ParsBERT](https://huggingface.co/HooshvareLab/bert-base-parsbert-uncased) model
### Results
|    Train Acc.   |   Train loss.   |   Test Acc.   |
| :-------------: | :-------------: | :-----------: |
|      0.88       |      0.30       |      0.81     |

## Data

[FarsTail](https://github.com/dml-qom/FarsTail): a Persian natural language inference dataset
