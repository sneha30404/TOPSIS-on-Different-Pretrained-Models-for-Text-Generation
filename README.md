# TOPSIS-on-Different-Pretrained-Models-for-Text-Generation

## Overview
This repository implements the TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) method to evaluate and rank popular pretrained text generation models based on multiple performance criteria.

###  Key Features
- **Evaluation Methodology:**
  - TOPSIS Multi-Criteria Decision Analysis
  - Weighted Criteria Evaluation
  - Ideal Solution Calculation

- **Pretrained Models Evaluated:**
  - GPT-4
  - PaLM 2
  - LLaMA 2
  - BLOOMZ
  - OPT-66B
  - T5-XXL

- **Evaluation Criteria:**
  - Perplexity Score
  - BLEU Score
  - Model Size
  - Inference Speed
  - Output Diversity

## Dataset
Model performance metrics collected from:
- Official model documentation
- Benchmarking studies
- Experimental results

## Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Evaluation Methodology
1. Criteria Weighting: Assign importance weights to evaluation metrics
2. Matrix Normalization: Transform raw metrics to comparable scales
3. Ideal Solutions: Calculate best/worst possible performance values
4. Distance Measurement: Compute Euclidean distances from ideal solutions
5. Ranking Calculation: Determine final model scores using closeness coefficients

## Results Visualization
### Closeness Coefficient Horizontal Bar Chart 
![image](https://github.com/user-attachments/assets/0befb8a8-7118-4187-b926-93f603bfab05)
Figure 1: Comparative visualization of model performance using TOPSIS methodology


### Multi-Criteria Radar Chart 
![image](https://github.com/user-attachments/assets/fd2ef4aa-e7d7-4916-81b3-46ac06e44f58)
Figure 2: Radar chart showing relative performance across different evaluation criteria
