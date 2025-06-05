
# 🧠 SentencePiece Tokenization on Tamil Dataset

This project demonstrates how to apply **SentencePiece**, an unsupervised subword tokenizer, to a **Tamil language dataset**. It showcases how subword tokenization can improve preprocessing in low-resource or morphologically rich languages like Tamil.

---

## 📁 File Structure

```
.
├── Spt.ipynb              # Main notebook for SentencePiece tokenization
├── README.md              # Project documentation
├── tamil_dataset/         # Folder containing Tamil text data (optional)
└── requirements.txt       # Required Python packages
```

---

## 🚀 Features

- 📚 Load and preprocess raw Tamil text data
- ✂️ Train SentencePiece tokenizer using BPE or Unigram
- 🧱 Tokenize and detokenize Tamil sentences
- 📊 Visualize vocabulary and token frequency
- 💾 Save and reuse trained tokenizers

---

## 🧪 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/tamil-sentencepiece.git
cd tamil-sentencepiece
```

### 2. Install required libraries

```bash
pip install -r requirements.txt
```

Or manually install:

```
sentencepiece
pandas
matplotlib
seaborn
```

### 3. Launch the notebook

```bash
jupyter notebook Spt.ipynb
```

---

## 🧰 Tools Used

- 🧠 **SentencePiece** – Subword tokenizer (BPE/Unigram)
- 📊 **Matplotlib & Seaborn** – Token frequency visualization
- 🐼 **Pandas** – Dataset handling

---
