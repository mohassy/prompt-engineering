# 🧠 Prompt Engineering with LangChain & GPT-4o

This project demonstrates and compares **six prompting strategies** using LangChain and OpenAI’s GPT-4o model in a Google Colab notebook. It focuses on solving multiple-choice reasoning problems programmatically.

## 📘 Prompting Techniques Implemented

1. **Direct Answer** – A basic prompt that requests an answer with no reasoning steps.
2. **Zero-shot CoT** – Adds a "Let's think step by step" nudge to encourage reasoning.
3. **Few-shot CoT** – Includes a few step-by-step solved examples before the actual question.
4. **Decomposition** – Breaks a complex problem into sub-problems and solves them.
5. **Self-Ask** – Uses intermediate follow-up questions to reach a final answer.
6. **Self-Consistency** – Samples multiple reasoning paths and picks the most consistent one.
7. **Multi-path Justification** – Evaluates each answer option individually and eliminates incorrect ones.

## 🔧 Technologies Used

- Python 3
- Hugging face API Key to get access to the GPQA dataset
- [LangChain](https://github.com/langchain-ai/langchain)
- OpenAI GPT-4o via `ChatOpenAI`
- Pydantic & Output Parsers
- Google Colab for execution

## 🚀 Getting Started

### Setup
1. Clone this repository.
2. Open the notebook in [Google Colab](https://colab.research.google.com/).
3. Use Hugging Face API Key to load GPQA dataset
4. Replace `"ENTER OPEN AI API KEY HERE"` with your actual OpenAI API key.
5. Run the cells and explore different prompting strategies
6. Run the analysis on the output to see how each technique performs

