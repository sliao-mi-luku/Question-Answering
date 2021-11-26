# Question-Answering
Deep Learning for Question Answering

## Projects in this repo:

1. SQuAD question answering
2. Visual question answering using ResNet + BERT
3. Visual question answering using Vision Transformer + BERT

## Question Answering

## References

**Implementation of BERT by Huggingface**

Pre-trained BERT using SQuAD 1.0:

```python
!pip install transformers

from transformers import BertForQuestionAnswering

model = BertForQuestionAnswering.from_pretrained('bert-large-uncased-whole-word-masking-finetuned-squad')
```
