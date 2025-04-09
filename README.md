# FairFrame_Media-Bias-Detection-and-Mitigation

- **Bias Detection:** Fine-tuned BERT model trained for bias score prediction (0–10 scale).
- **Bias Mitigation:** A T5-based rewriter trained on original + Mixtral-generated neutral sentences.
- **Feedback Loop:** Re-evaluates mitigated text until the bias score is reduced adequately.

---

## 📁 Dataset Sources

This project combines multiple curated datasets got through the reference from MBIB :
- [BABE](https://www.kaggle.com/datasets/timospinde/mbib-media-bias-identification-benchmark)
- [BASIL](https://www.kaggle.com/datasets/timospinde/mbib-media-bias-identification-benchmark)
- [NPOV Wikipedia Dataset](https://www.kaggle.com/datasets/timospinde/mbib-media-bias-identification-benchmark)
- [Multidimensional Bias](https://www.kaggle.com/datasets/timospinde/mbib-media-bias-identification-benchmark)

---

## 🧠 Technologies Used

- Python 🐍
- PyTorch / Huggingface Transformers
- Google Colab
- BERT (for bias detection)
- T5 (for text mitigation)
- Mixtral (mitigation dataset creation)

---
