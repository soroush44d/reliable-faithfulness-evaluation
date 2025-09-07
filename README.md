NLP Final Project – Faithfulness Evaluation in Summarization
📌 Project Overview

This project focuses on evaluating faithfulness in abstractive text summarization.
We work with the XSum and XSumFaithful datasets to analyze how well generated summaries remain true to the source text.

Our goal is to design automated evaluation metrics that can detect:

✅ Accurate information retention

❌ Contradictions with the source text

📉 Uncertainty at the token level (via entropy)

The project implements two main approaches (A and B), leveraging LLM-based evaluation (Gemini 1.5-flash-8b) and traditional statistical methods.

