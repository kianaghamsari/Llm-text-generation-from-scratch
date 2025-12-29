# LLM Text Generation from Scratch

This project implements a text generation model from scratch using Python and PyTorch.
The model was trained on a subset of the Persian Wikipedia dataset.

> This project was originally developed as part of a university course.

## Overview
- Implemented a language model using Embedding + LSTM + Fully Connected layers
- Built custom dataset and training loop without using pre-trained models
- Evaluated the model using Perplexity and ROUGE metrics

## Engineering Challenges
- High RAM usage when processing large text datasets
- Long training time on full dataset

## Solutions
- Reduced dataset size during development and scaled gradually
- Tuned batch size, sequence length, and model complexity
- Used GPU acceleration to improve training performance

## Tech Stack
- Python
- PyTorch
- Jupyter Notebook

## Contents
- `notebook.ipynb`: model implementation and experiments
- `report.pdf`: detailed technical report and analysis
