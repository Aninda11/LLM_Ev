# Phishing LLM Trustworthiness Evaluation

This project evaluates the **bias, trustworthiness, and fairness** of open LLMs in phishing-related contexts.

## Models Used
- Qwen2.5-7B-Instruct
- Mistral-7B-Instruct-v0.3
- TinyLlama-1.1B-Chat-v1.0

## What This Project Does
- runs phishing-related prompts on 3 LLMs
- saves model responses
- scores the responses manually
- compares the models using tables and graphs

## Prompt Categories
- victim-support prompts
- fairness prompts
- stereotype-bias prompts
- malicious-use prompts

## Main Files
- `notebook.ipynb` — main Colab notebook
- `all_model_outputs_3models.csv` — all generated responses
- `scored_outputs_3models.csv` — manually scored results
- `overall_summary_3models.csv` — overall results
- `category_summary_3models.csv` — category-wise results
- `fairness_gap_summary_3models.csv` — fairness-gap results
- `refusal_summary_3models.csv` — refusal results

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU
3. Install required packages
4. Run the cells step by step
5. Generate outputs for all models
6. Score the outputs
7. Run the analysis section

## Required Packages
```python
pip install transformers accelerate bitsandbytes sentencepiece pandas matplotlib
