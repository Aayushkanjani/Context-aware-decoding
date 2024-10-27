# Reducing Hallucinations in Large Language Models (LLMs)

This project aims to address and mitigate hallucinations in large language models (LLMs) by implementing advanced techniques such as context-aware decoding, reinforcement learning, and data curation. LLM hallucinations—responses generated by the model that seem plausible but are incorrect—pose challenges to reliability and usability. This repository provides tools, insights, and best practices to reduce these hallucinations effectively.

## Table of Contents
- [Introduction](#introduction)
- [What Are LLM Hallucinations?](#what-are-llm-hallucinations)
- [Why Do LLMs Hallucinate?](#why-do-llms-hallucinate)
- [Impact of Hallucinations](#impact-of-hallucinations)
- [Getting Started](#getting-started)
- [Usage](#usage)


## Introduction

Large Language Models (LLMs) have become increasingly powerful but can sometimes produce "hallucinations"—false or misleading information. This project explores the root causes of these hallucinations and provides practical approaches to reduce their frequency, focusing on context-aware decoding and advanced fine-tuning techniques.

## What Are LLM Hallucinations?

Hallucinations in LLMs refer to responses that are syntactically correct but factually incorrect or contextually misplaced. These responses arise because the model generates content based on probabilities without a true understanding of the facts.

## Why Do LLMs Hallucinate?

LLMs are trained on vast datasets but lack the capability to distinguish factual information from patterns. Hallucinations result from:
- Training on mixed-quality data
- Limited world knowledge or context
- Lack of real-world grounding or factual verification

## Impact of Hallucinations

Hallucinations can impact:
- **User Trust**: Undermining the reliability of LLM-based applications.
- **Information Quality**: Providing incorrect responses that can mislead users.
- **Application Suitability**: Reducing applicability in critical areas like healthcare or legal advisory.


## Getting Started

### Prerequisites
- Python 3.8 or higher
- `transformers` library by Hugging Face
- `torch` library for PyTorch support

### Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/Aayushkanjani/Context-aware-decoding.git
cd Context-aware-decoding
```

## Usage
Run the example notebook to see techniques in action:<br>
**jupyter notebook example_notebook.ipynb**



