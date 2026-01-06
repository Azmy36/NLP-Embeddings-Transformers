# 🗣️ NLP Embeddings & Transformers

This repository explores fundamental and advanced techniques in **Natural Language Processing (NLP)**, ranging from traditional **Word Embeddings** to state-of-the-art **Transformer Fine-Tuning**.
It serves as a comprehensive guide to understanding how machines interpret human language, moving from static vector representations to dynamic, context-aware models.

> **⚠️ Important:**
> This repository is divided into two main components: geometric analysis of word vectors and practical application of large language models.

## 📌 Features

- **Word Embeddings Analysis**:
    - Utilization of **Word2Vec** and **GloVe** via `Gensim`.
    - Visualization of semantic relationships (analogies, clustering).
- **Transformer Fine-Tuning**:
    - Implementing and fine-tuning Transformer architectures (e.g., BERT/DistilBERT) for downstream tasks.
    - Leveraging pre-trained models from **Hugging Face**.
- **Frameworks**: Built using **TensorFlow**, **Gensim**, and **Scikit-Learn**.

## 🧠 Components

### **1. Word Embeddings (`Word_Embeddings_Analysis.ipynb`)**
- Focuses on static embeddings where each word maps to a fixed vector.
- Demonstrates vector arithmetic (e.g., *King - Man + Woman = Queen*).
- Visualizes high-dimensional data using PCA/t-SNE.

### **2. Transformer Fine-Tuning (`Transformer_FineTuning.ipynb`)**
- Focuses on context-aware embeddings (Self-Attention).
- Loads a pre-trained Transformer model.
- Fine-tunes the model on a specific dataset (e.g., sentiment analysis or classification).

## 📂 Repository Structure

```
.
├── Word_Embeddings_Analysis.ipynb  # Exploration of Word2Vec/GloVe
├── Transformer_FineTuning.ipynb    # Fine-tuning workflow for Transformers
└── README.md                       # Project documentation
```

## ⚙️ Installation & Usage

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Azmy36/NLP-Embeddings-Transformers.git
    cd NLP-Embeddings-Transformers
    ```

2.  **Install dependencies**:
    ```bash
    pip install tensorflow gensim scikit-learn pandas transformers matplotlib
    ```

3.  **Run the Notebooks**:
    - Use `Word_Embeddings_Analysis.ipynb` for fundamental concepts.
    - Use `Transformer_FineTuning.ipynb` for modern NLP applications.

## 👨‍💻 Author

**Youssef Mohamed Moussa**
- 📧 Email: [youssefazmy36@gmail.com](mailto:youssefazmy36@gmail.com)
