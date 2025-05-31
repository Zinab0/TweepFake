# TweepFake: Twitter Deepfake Detection

This repository contains the implementation of machine learning models for detecting deepfake tweets on Twitter, as described in our research paper "TweepFake: Twitter deep fake detection using machine learning approaches".

## Overview

We evaluated four state-of-the-art machine learning models for detecting bot-generated tweets:
- **RoBERTa** (Best performance: 82.41% accuracy)
- **BERT** (80.21% accuracy)
- **SVM** (69% accuracy) 
- **BiLSTM** (68% accuracy)

## Dataset

The study uses the TweepFake dataset containing 25,836 tweets equally divided between human-generated and bot-generated content from 23 bots and 17 human accounts.

**Dataset source**: [TweepFake Dataset](https://github.com/tizfa/tweepfake_deepfake_text_detection/tree/master)


## Results

| Model    | Accuracy | Precision | Recall | F1-Score |
|----------|----------|-----------|--------|----------|
| RoBERTa  | 82.41%   | 82.99%    | 82.40% | 82.33%   |
| BERT     | 80.21%   | 80.42%    | 80.21% | 80.18%   |
| SVM      | 69.00%   | 70.00%    | 70.00% | 70.00%   |
| BiLSTM   | 68.00%   | -         | -      | -        |


