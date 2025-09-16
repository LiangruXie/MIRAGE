# MIRAGE
## Overview

MIRAGE is a robust uncertainty calibration framework for Retrieval-Augmented Generation (RAG) that addresses the critical challenge of unreliable uncertainty estimation in high-stakes applications and content recommendation. By jointly modeling retrieval-induced and raw uncertainties, MIRAGE provides trustworthy uncertainty estimates for RAG systems.

## Architecture

MIRAGE consists of two main components:

1. **MIR-N (Noise Estimation)**: Estimates retrieval-induced uncertainty using pointwise mutual information
2. **MIR-C (Calibration)**: Bayesian Neural Network-based calibrator for uncertainty interactions

## Installation

```bash
git clone https://github.com/username/MIRAGE.git
cd MIRAGE
pip install -r requirements.txt
```

## Quick Start

## Datasets

We evaluate MIRAGE on four domains:

- **General Knowledge**: From RGB
- **Finance \& Movies**: From CRAG
- **Biomedical**: From RAGBench

the path is
```bash
./data
```
