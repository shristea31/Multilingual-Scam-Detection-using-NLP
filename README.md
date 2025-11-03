**Multilingual Scam Detection (English–Hinglish) using NLP**

A Transformer-based Natural Language Processing (NLP) project designed to detect and classify scam messages across multiple languages (English and Hinglish) from WhatsApp and SMS datasets.  
The project leverages **BERT-based Transformers** for multilingual text understanding and classification.

---

 🚀 **Project Overview**
Scam messages on social media and messaging platforms are increasing rapidly.  
This project focuses on detecting multilingual scam messages using **Transformer architectures (BERT)** fine-tuned on a custom multilingual dataset.

The notebook demonstrates:
- Text cleaning, normalization, and preprocessing for multilingual (Hinglish–English) text.
- Dataset Visulaization for Understanding
- Training an TF-IDF model and testing it on the dataset for a baseline benchmark
- Tokenization and embedding generation using `BERT tokenizer`.
- Model fine-tuning and training on labeled scam/ham messages.
- Evaluation through accuracy, precision, recall, and F1-score.

---

 🧠 **Key Features**
- Multilingual (Hinglish–English) text support
- Data preprocessing and normalization pipeline
- BERT model fine-tuning for binary classification
- Dataset balancing and augmentation
- Evaluation metrics visualization

---

 📊 **Model Performance**
| Metric | Score |
|--------|--------|
| **Accuracy** | ~96% |
| **Precision** | 0.96 |
| **Recall** | 0.95 |
| **F1-Score** | 0.95 |

---

 🧩 **Dataset**
The dataset includes **WhatsApp** and **SMS** messages labeled as:
- **1 → Scam**
- **0 → Ham (Not Scam)**

> The dataset was curated manually for academic use and contains Hinglish + Hindi  text samples.
> The dataset for English samples is taken from Github. (LINK: https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv)


---

 🧰 **Tech Stack**
- **Python 3**
- **Transformers (Hugging Face)**
- **PyTorch / TensorFlow**
- **Scikit-learn**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Google Colab**

---

⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shristea31/Multilingual-Scam-Detection-using-NLP.git
   cd Multilingual-Scam-Detection-using-NLP
