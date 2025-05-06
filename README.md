# Feeling Anxious About the Election? Analyzing Political Anxiety on TikTok During the 2024 U.S. Presidential Elections

This repository contains supporting materials for the paper  
**"Feeling Anxious About the Election? Analyzing the Landscape of Political Anxiety on TikTok During the 2024 U.S. Presidential Race"**

---

## 📁 Repository Contents

### `election_data.csv`
A file containing anonymized TikTok video IDs used in our study. These videos come from the 2024 TikTok Election Dataset and were filtered to include only:
- Videos with transcriptions
- No background music
- At least 15 words of spoken content

### `mistral_instruct_finetuning.ipynb`
A Jupyter notebook used to fine-tune the `Mistral-7B-Instruct-v0.2` model via Hugging Face Transformers and PEFT with LoRA.  
It includes:
- Instruction-tuning prompt formatting
- Tokenization and LoRA setup
- Training configuration and evaluation

### `finetuned_large_scale_inference.ipynb`
This notebook performs large-scale classification using the fine-tuned model. It processes TikTok transcripts and assigns each video a political leaning (`Left-Leaning`, `Right-Leaning`, or `Neutral`).

---

## 🔐 Ethics and Privacy

- All TikTok videos were publicly available at the time of collection.
- Usernames, user IDs, and any personally identifiable information have been removed.
- Analyses are conducted at the aggregate level, not at the individual level.
- Research was conducted in line with ethical standards for public social media data.

---
