# Wekeza LLM — Self-Instruct v2

This notebook fine-tunes a small causal language model (DistilGPT2) using the Self-Instruct method to improve investment-focused responses for Kenyan retail investors.

### 🧠 Objective
Apply the Self-Instruct technique to generate and fine-tune on a high-quality, Alpaca-formatted dataset specific to money market fund investing in Kenya.

### 🔧 Model
- Base model: `distilgpt2`
- Fine-tuning method: Full fine-tuning using `Trainer`
- Dataset: Custom instruction dataset (`WekezaLLM_dataset_v2.jsonl`) created manually
- Output model: `distilgpt2-wekeza-finetuned_v2`

### 📁 Structure
- `notebook.ipynb` — full fine-tuning pipeline with tokenization, training, and saving.
- `WekezaLLM_dataset_v2.jsonl` — instruction dataset.
