# 🏦 Banking Chatbot — Deep Learning Project

A conversational banking chatbot built using a modular deep learning pipeline.
Developed as a group assignment for our Deep Learning course.

## Roles

| NLP & Intent Classification 
| Entity Extraction (NER) 
| RAG & Embeddings 
| Response Generation 
| Model Evaluation & Integration 

## 🧠 Models Used
| Component | Model |
|---|---|
| Intent Classification | BERT fine-tuned on BANKING77 |
| Entity Extraction | BERT-NER fine-tuned |
| RAG Embeddings | sentence-transformers/all-MiniLM-L6-v2 |
| Response Generation | google/flan-t5-base |

## 📦 Datasets
- [BANKING77](https://huggingface.co/datasets/banking77) — Intent classification
- BERT-NER training data — Entity extraction
- Custom banking FAQ documents — RAG pipeline

## 🚀 How to Run
1. Clone the repo
   git clone https://github.com/your-username/banking-chatbot-dl.git

2. Install dependencies
   pip install -r requirements.txt

3. Run notebooks in order (01 → 05)

## 📊 Evaluation Metrics
- Intent Classification: Accuracy, F1-Score
- NER: Precision, Recall, F1
- Response Generation: BLEU Score

## 🛠️ Tech Stack
Python, HuggingFace Transformers, Sentence Transformers, ChromaDB, PyTorch, Jupyter
