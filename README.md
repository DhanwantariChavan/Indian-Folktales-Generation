# Indian-Folktales-Generation
Generate captivating Indian folktales with a fine-tuned GPT-2–style model

# Project Overview
A Jupyter-based pipeline that ingests a curated corpus of Indian folktales, performs exploratory data analysis, preprocesses text, and fine-tunes a GPT-2 language model to generate new stories. Ideal for researchers, educators, and storytellers looking to explore AI-driven folklore creation.

# Dataset:
cleaned_stories.csv

# Features

Data Ingestion & Exploration: Load CSV/JSON data, visualize story lengths and word frequencies.

Cleaning & Preprocessing: Normalize text, remove noise, apply stopword filtering.

Dataset Preparation: Convert to Hugging Face Dataset, split into train/validation sets.

Tokenization: Use GPT2Tokenizer with custom special tokens and dynamic padding/truncation.

Fine-Tuning: Leverage GPT2LMHeadModel and Hugging Face Trainer API with configurable hyperparameters.

Generation: Produce new folktales via controllable sampling (top‑k, top‑p, temperature).

Visualization: Histograms, word clouds, and bar plots to understand data distribution.
