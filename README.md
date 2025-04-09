# FairFrame_Media-Bias-Detection-and-Mitigation
Fairframe is an AI-powered system for detecting and mitigating bias in media content. It combines state-of-the-art transformer models to analyze news text for subjective bias and rephrase biased content into neutral and objective language. This project is designed to promote responsible journalism, reduce misinformation, and empower readers with a clearer understanding of how bias shapes narratives.

Fairframe supports a full bias moderation pipeline:

📊 Bias Detection using fine-tuned BERT models that score sentences on a 0–10 scale.

✍️ Bias Mitigation using a T5-based model (assisted by Mixtral for training data generation) to rewrite biased text.

🔁 Feedback Loop that re-evaluates mitigation until the output achieves a lower bias score.

📚 Built on top of trusted datasets: BABE, BASIL, NPOV, and MBIB for training and evaluation.

🛠️ Easy to integrate and built for real-world application in journalism and NLP research.

Whether you're a researcher, journalist, or developer, Fairframe provides an accessible framework for studying, measuring, and countering media bias in a responsible, scalable way.
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
