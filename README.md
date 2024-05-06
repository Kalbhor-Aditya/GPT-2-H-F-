# GPT2 with Hugging Face

This project utilizes the GPT-2 large model from the Hugging Face's transformers library for Natural Language Processing tasks.

## Model

The main model used in this project is the GPT-2 large model. The model and its tokenizer are loaded as follows:

```
python
from transformers import GPT2Tokenizer, GPT2LMHeadModel

tokenizer = GPT2Tokenizer.from_pretrained('gpt2-large')
model = GPT2LMHeadModel.from_pretrained("gpt2-large", pad_token_id=tokenizer.eos_token_id)

```

## Requirements

transformers

torch

pip install transformers torch

## Usage

You can use the GPT-2 large model for various NLP tasks such as text generation, translation, summarization etc.
