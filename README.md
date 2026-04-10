# Sentiment Analysis - Deep Learning Project

## Overview
A deep learning project that classifies movie reviews as
positive or negative using an LSTM neural network.

## Dataset
- Source: IMDB Movie Reviews (TensorFlow built-in)
- Total Reviews: 50,000
- Classes: Positive (50%) and Negative (50%)

## Model Architecture
- Embedding Layer (vocab: 10,000 words)
- LSTM Layer (64 units)
- Dropout Layer (0.5)
- Dense Layers (32 → 1)

## Results
| Metric   | Score  |
|----------|--------|
| Accuracy | 80.50% |
| Loss     | 0.5015 |

## Sample Predictions
| Review | Sentiment | Confidence |
|--------|-----------|------------|
| "This movie was absolutely fantastic" | POSITIVE | 88.12% |
| "Terrible film waste of time" | NEGATIVE | 10.98% |
| "Boring plot bad acting hated it" | NEGATIVE | 9.67% |
| "Best movies I have ever watched" | POSITIVE | 89.20% |

## How to Run
1. Open notebook in Google Colab
2. Run all cells in order
3. Model trains automatically
4. Test custom reviews in the last cell

## Saved Model
sentiment_model.h5 — 16.29 MB

## Internship
Built as Task 2 of the AI Internship at InternSpark.
