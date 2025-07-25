# 🧠 LLM Output Evaluator – Python Prompt Testing Tool

A lightweight Python project designed to simulate real-world LLM (Large Language Model) evaluation workflows. This tool allows users to test prompts against a language model (like OpenAI's GPT), collect responses, and score them based on clarity, tone, factual accuracy, completeness, and ethical considerations.

## 🔍 Features

- Submit a list of prompts to an LLM
- Collect and store model responses in CSV
- Manual or scripted evaluation of response quality
- Simple scoring rubric and comment system
- Extendable for bias detection or tone classification

## 📂 File Structure

- `prompt_tester.py` – Python script to send prompts and log results
- `sample_results.csv` – Example dataset of responses for scoring
- `eval_criteria.md` – Markdown file describing evaluation metrics
- `README.md` – This file

## 📝 Evaluation Criteria

| Category           | Scale / Notes                          |
|--------------------|-----------------------------------------|
| Factual Accuracy   | 0–5 scale (5 = fully accurate)          |
| Relevance          | 0–5 scale (5 = completely on topic)     |
| Tone Appropriateness | Friendly / Neutral / Formal           |
| Completeness       | Partial / Adequate / Thorough           |
| Ethical Safety     | Pass / Flag                             |

## 🧪 Sample Use

```bash
$ python prompt_tester.py
Prompt: Explain the blockchain in 100 words or less.
Response: [Model Output]
```

## 🧠 Example Prompts

1. Explain reinforcement learning to a 12-year-old.
2. Describe the symptoms and treatment of generalized anxiety disorder.
3. Write a formal apology email to a customer whose order was delayed.
4. List three benefits and three drawbacks of using AI in public health.
5. Create a motivational quote about learning.

## 🛠️ Future Enhancements

- GUI using Tkinter or Gradio
- Auto-score system with red-flag keyword detection
- Compare responses from multiple LLMs

## 📘 License

MIT License

---

### 📄 Technical Writing Sample

**[How to Evaluate AI Prompts – PDF](https://github.com/geegorbee/LLM-Prompt-Evaluator/blob/main/How_to_Evaluate_AI_Prompts_Gerald_Brown.pdf)**  
A short, instructional guide that outlines a rubric-driven framework for evaluating large language model (LLM) outputs. Covers criteria like accuracy, clarity, completeness, and ethical safety. Designed as a demonstration of technical communication and human-in-the-loop evaluation strategies.

---
