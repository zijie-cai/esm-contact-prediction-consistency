# ESM vs. MSA: A Consistency Analysis in Protein Contact Prediction

This repository provides a framework to analyze the consistency of protein contact predictions between Meta’s LLM-based Evolutionary Scale Modeling (ESM) and predictions derived from Multiple Sequence Alignments (MSA). It focuses on comparing pairwise contact predictions for sequences within a protein family retrieved from the PFAM database.

**Author:** Zijie Cai

---

## Overview

This analysis involves the following steps:

1. **Download PFAM Seed Alignment & Basic Analysis:**  
   - Input a PFAM ID and fetch the seed alignment from the PFAM database.
   - Perform initial analyses such as pairwise sequence identity calculations.

2. **Select and Load an ESM-2 Model:**  
   - Choose from a set of ESM-2 models.
   - Load the selected model to generate protein contact predictions.

3. **Pairwise Contact Prediction & Visualization:**  
   - Select two sequences from the alignment.
   - Generate and visualize contact maps using ESM-2.
   - Explore adjustable thresholds, residue distances, and compute consistency scores for benchmarking ESM predictions against MSA-based insights.

The goal is to understand where ESM excels in contact prediction and where traditional MSA-based methods might have advantages or complementarities.

---

## Getting Started

### Run in Google Colab

Click the badge below to directly open and run the notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-btn.svg)](https://colab.research.google.com/drive/1wz8o5HeZKbKzjjCMBisdzUlsUw6fF_g1?usp=sharing)

Make sure you have a Google account and are logged in to view and run the notebook.

### Running Locally

**Requirements:**

- Python 3.7+
- `torch`
- `biopython`
- `numpy`
- `matplotlib`
- `ipywidgets`
- `esm` (Meta’s ESM library)

You can install dependencies via:
```bash
pip install torch biopython numpy matplotlib ipywidgets fair-esm
