# FairFrame_Media-Bias-Detection-and-Mitigation

- **Bias Detection:** Fine-tuned BERT model trained for bias score prediction (0–10 scale).
- **Bias Mitigation:** A T5-based rewriter trained on original + Mixtral-generated neutral sentences.
- **Feedback Loop:** Re-evaluates mitigated text until the bias score is reduced adequately.

---

## 📁 Dataset Sources

This project combines multiple curated datasets:
- [BABE](https://huggingface.co/datasets/babe)
- [BASIL](https://github.com/successar/BASIL)
- [NPOV Wikipedia Dataset](https://figshare.com/articles/dataset/Wikipedia_NPOV_Dataset/20607784)
- [MBIB Dataset](https://aclanthology.org/2023.acl-long.645/) – Multidimensional Bias in News

---

## 🧠 Technologies Used

- Python 🐍
- PyTorch / Huggingface Transformers
- Google Colab
- BERT (for bias detection)
- T5 / Mixtral (for text mitigation)
- ViT-B/32 (for multimodal expansion – optional)

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/fairframe.git
cd fairframe
