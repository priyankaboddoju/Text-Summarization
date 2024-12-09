# Efficient Text Summarization for Long Documents

This project explores the development of a robust approach to summarizing long documents efficiently using enhanced abstractive summarization techniques. The solution employs fine-tuned transformer models and a curated dataset to produce coherent, concise summaries.

## Overview

The project aims to address the challenge of summarizing lengthy documents such as news articles, legal texts, and scientific papers. By leveraging modern Natural Language Processing (NLP) techniques, the proposed model improves both the quality and efficiency of text summarization.

## Features

- **Model Architecture**: Fine-tuned abstractive summarization model based on BART.
- **Datasets**: 
  - Pre-trained on the CNN/DailyMail dataset.
  - Fine-tuned using a curated subset for improved contextual understanding.
- **Evaluation Metrics**: ROUGE-1, ROUGE-2, and ROUGE-L were used for benchmarking.
- **Enhanced Performance**: The enhanced implementation shows significant improvements in F-measure compared to the baseline code.

## Methodology

1. **Data Preprocessing**:
   - Processed CNN/DailyMail dataset.
   - Curated dataset was created for domain-specific summarization.
2. **Model Development**:
   - Fine-tuning of BART for abstractive summarization tasks.
   - Optimized using PyTorch Lightning.
3. **Evaluation**:
   - ROUGE metrics calculated to compare performance.
   - Improved F-measure (+0.039) in ROUGE-1 and ROUGE-L metrics.

## Results

| Metric       | Precision (Old) | Recall (Old) | F-Measure (Old) | Precision (Enhanced) | Recall (Enhanced) | F-Measure (Enhanced) | Improvement |
|--------------|-----------------|--------------|------------------|-----------------------|--------------------|-----------------------|-------------|
| ROUGE-1      | 0.051           | 0.429        | 0.091            | 0.077                 | 0.429              | 0.130                 | +0.039      |
| ROUGE-2      | 0.000           | 0.000        | 0.000            | 0.000                 | 0.000              | 0.000                 | No Change   |
| ROUGE-L      | 0.051           | 0.429        | 0.091            | 0.077                 | 0.429              | 0.130                 | +0.039      |

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch 1.10+
- Hugging Face Transformers
- PyTorch Lightning

### Video Demo

Watch the project demonstration on YouTube:

[![Project Demo](https://img.youtube.com/vi/i3tA6Vbo6Cc/maxresdefault.jpg)](https://youtu.be/i3tA6Vbo6Cc?si=flJZa_oT9Mhd46YF)
