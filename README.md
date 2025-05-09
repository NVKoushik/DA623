# Meme classification: Multimodal hate speech detection
**DA623 Course Project - Winter 2025**  
by **Venkata Koushik Nagasarapu**

---

## 📚 Overview
This project explores the **Hateful Memes Challenge** — a benchmark designed to detect hate speech in memes using **multimodal reasoning** (combining text and images).  
Memes are powerful but sometimes harmful communication tools, and detecting hate within them requires going beyond simple text or image classifiers.

---

## 🚀 Project Highlights

- **Dataset:** 10,000 memes annotated for hatefulness, with specially created *benign confounders* that force models to use both modalities.
- **Task:** Binary classification — hateful vs. non-hateful memes.
- **Models Explored:**
  - Logistic Regression with **TF-IDF** (text-only)
  - Logistic Regression with **ResNet50 features** (image-only)
  - Fusion model combining both

---

## 📊 Example Outputs

- 📈 **Text length distributions**
- 🔥 **Top words** in hateful vs. non-hateful memes
- 🖼️ **Sample memes** and their benign confounders
- 🎯 **Baseline AUROC scores:**
  - Text-only: ~69%
  - Image-only: ~53%
  - Fusion: ~74%

---

## 📓 Jupyter Notebook

Explore the full code and experiments in my notebook:  
👉 [hateful_memes_eda.ipynb](210108030_DA623.ipynb)

This includes:
- Data loading and exploration
- Text length histograms & word counts
- Sample meme visualization
- Baseline model training (Text-only, Image-only, Fusion)

---

## 🎥 Presentation Video (10 mins)

Watch my recorded walkthrough here:  
**▶️ [YouTube Video Link](https://youtu.be/QhOXD-4Lw08)**

---

## 🔥 Key Learnings

- Multimodal reasoning is **essential** — neither text nor image alone is enough.
- State-of-the-art models still lag behind human performance.
- Dataset construction using benign confounders is a powerful way to neutralize model shortcuts.

---

## 📚 References

- **Paper:** [The Hateful Memes Challenge](https://arxiv.org/abs/2005.04790)
- **Dataset & Code:** [Facebook AI MMF repo](https://github.com/facebookresearch/mmf/tree/main/projects/hateful_memes)

---

## 👨‍💻 Author
**Venkata Koushik Nagasarapu**  
B.Tech, Electronics and Electrical Engineering, IIT Guwahati
