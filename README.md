**Information_Extraction_Prompt_Engineering**
This project focuses on prompt engineering techniques for structured information extraction:
•	Demonstrates advanced prompt engineering techniques for structured information extraction, showcasing zero-shot, few-shot, and chain-of-thought prompting using OpenAI and Mistral models.


**Fine_Tuning_QLoRA_Axolotl**
This project explores fine-tuning large language models using Axolotl with QLoRA. It includes:
•	Fine-tuning Qwen/Qwen3-1.7B-Base and Qwen3-1.7B-Instruct on extraction tasks 
•	Inference with vLLM on the test split using LoRA adapters.
•	Evaluation of model performance using strict matching and F1 score.
•	Zero-shot inference using OpenAI’s GPT-4 for benchmarking against fine-tuned models.
•	Final comparison highlights the trade-offs between parameter-efficient tuning, instruction-tuned models, and API-based solutions.


**Query_Decomposition_RAG_Renaker**
This project implements Retrieval-Augmented Generation (RAG) pipelines for comparative document analysis:
•	Analyzes SEC 10-K filings.
•	Implements both a standard RAG pipeline and a query decomposition-based RAG pipeline to break down the main question into focused sub-queries.
•	Compares the results from both approaches in terms of completeness and response quality, providing insight into the effectiveness of query decomposition in RAG workflows.
