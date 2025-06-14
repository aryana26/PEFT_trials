# IMDB Sentiment Classification using PEFT Techniques (Prompt Tuning, Adapters, LoRA)

In this I have explored parameter-efficient fine-tuning (PEFT) methods to adapt the `t5-small` language model for **sentiment classification** (positive/negative) of IMDB movie reviews using **Google Colab's free GPU**.

compared methods included-
- 🔧 **Prompt Tuning**
- 🧩 **Adapters**
- 🪶 **LoRA (Low-Rank Adaptation)**

---

## 💡 Objective

Given a movie review from the IMDB dataset, classify it as **positive** or **negative** using a small, efficient LLM (`t5-small`) with various PEFT methods instead of full fine-tuning.

---

---

## 📚 Dataset

- **IMDB Reviews** (binary sentiment classification)
- Source: Hugging Face Datasets  
