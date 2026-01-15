# Customer-Support-Bot

A context-aware FAQ chatbot built using **BERT** and **Hugging Face Transformers**.  
This project demonstrates how transformer-based language models can be used for **question answering** over custom business data.

The chatbot takes a user question and extracts the most relevant answer directly from a provided knowledge context.

---

## 🚀 Features

- Uses **BERT for Question Answering**
- Context-based responses (no hardcoded answers)
- Powered by **Hugging Face Transformers**
- Built with **PyTorch**
- Easily extendable to other models (RoBERTa, DistilBERT)
- Suitable for FAQ systems, customer support, and prototypes

---

## 🧠 How It Works

1. The user asks a question
2. The question and business context are combined
3. The tokenizer converts text into tokens and embeddings
4. BERT predicts:
   - **Start token**
   - **End token**
5. The answer span is extracted from the context

---

## Conda Environment (Optional but Recommended)
```bash
conda create -n faq_chatbot python=3.11 -y
conda activate faq_chatbot
pip install torch transformers sentencepiece numpy
```

## Environment Requirements

- Python 3.9+
- PyTorch
- Hugging Face Transformers

### Install Dependencies
```bash
pip install -r requirements.txt
```
