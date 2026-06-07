# CS5001NLP-Table-To-Text-Project

# CS5001 NLP – Table-To-Text Generation Using LLMs

> Comparing Large Language Models for structured table-to-text generation using BART, Gemini, and Mistral.

---

## 📌 Overview

This project explores the task of **Table-To-Text Generation** — automatically converting structured tabular data into fluent natural language descriptions. We compare three state-of-the-art language models:

- **BART** – A sequence-to-sequence model from Meta AI
- **Gemini** – Google's multimodal large language model
- **Mistral** – An open-source efficient LLM

The goal is to evaluate which model produces the most accurate, fluent, and faithful text descriptions from structured table inputs.

---

## 📁 Repository Structure

```
├── bart/                  # BART model implementation & results
├── gemini/                # Gemini model implementation & results
├── mistral/               # Mistral model implementation & results
├── overall_results/       # Combined evaluation & comparison results
├── requirements.txt       # Python dependencies
└── README.md
```

---

## 🧠 Models Compared

| Model | Type | Source |
|-------|------|--------|
| **BART** | Seq2Seq Transformer | Meta AI (HuggingFace) |
| **Gemini** | Multimodal LLM | Google DeepMind |
| **Mistral** | Decoder-only LLM | Mistral AI |

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yaswanth0702/NLP-Table-To-Text-Using-LLM.git
cd NLP-Table-To-Text-Using-LLM

# Install dependencies
pip install -r requirements.txt
```

---

## 🚀 How to Run

Each model has its own folder. Navigate to the respective folder and run:

```bash
# For BART
cd bart/
python run.py

# For Gemini
cd gemini/
python run.py

# For Mistral
cd mistral/
python run.py
```

> Results for each model are saved in their respective folders and summarized in `overall_results/`.

---

## 📊 Evaluation Metrics

Models are evaluated using standard NLG (Natural Language Generation) metrics:

| Metric | Description |
|--------|-------------|
| **BLEU** | Measures n-gram overlap with reference text |
| **ROUGE** | Recall-oriented overlap for summarization |
| **METEOR** | Considers synonyms and paraphrases |
| **BERTScore** | Semantic similarity using BERT embeddings |

---

## 📈 Results

> See `overall_results/` folder for detailed comparison outputs.

| Model | BLEU | ROUGE-L | BERTScore |
|-------|------|---------|-----------|
| BART | - | - | - |
| Gemini | - | - | - |
| Mistral | - | - | - |

*(Fill in your actual scores from overall_results/)*

---

## 🔍 Key Findings

- *(Add your key observations after comparing models)*
- *(e.g., "Gemini produced more fluent descriptions but BART was more faithful to table values")*

---

## 📚 References

- Lewis et al. – BART: Denoising Sequence-to-Sequence Pre-training (ACL 2020)
- Gemini Team, Google – Gemini: A Family of Highly Capable Multimodal Models (2023)
- Jiang et al. – Mistral 7B (arXiv 2023)
- Parikh et al. – ToTTo: A Controlled Table-To-Text Generation Dataset (EMNLP 2020)

---

## 👤 Author

**Yaswanth Podapati**  
Missouri University of Science and Technology  
GitHub: [@yaswanth0702](https://github.com/yaswanth0702)

---

## 📄 License

This project is for academic purposes – CS5001 NLP Course, Missouri S&T.
