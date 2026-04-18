# Glassdoor Turnover Analysis (NLP + Machine Learning)

## Overview
This project builds a machine learning framework to predict employee turnover risk and identify key drivers of dissatisfaction using Glassdoor reviews.

## Problem
Employee turnover is costly for organizations. This project answers:
1. Who is likely to leave?
2. Why are they leaving?

## Methods
- NLP Feature Engineering:
  - Sentence-BERT embeddings
  - NRC Emotion Lexicon
- Feature Processing:
  - PCA for dimensionality reduction
  - Frequency encoding for high-cardinality features
- Modeling:
  - Multi-class classification (rating prediction)
  - Binary classification (turnover risk)
  - XGBoost / MLP

## Results
- Turnover prediction accuracy: 91%
- Identified key drivers:
  - Management issues dominate
  - Compensation less significant

## Files
- `notebooks/`: modeling code
- `docs/`: final report
- `resources/`: lexicon data

## Business Impact
Provides actionable insights for HR teams to reduce employee turnover through targeted interventions.
