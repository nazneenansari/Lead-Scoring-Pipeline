# 🧠 Lead-Scoring Pipeline

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Build Status](https://img.shields.io/github/actions/workflow/status/nazneenansari/Lead-Scoring-Pipeline/tests.yml?branch=main)](https://github.com/nazneenansari/Lead-Scoring-Pipeline/actions)
[![Issues](https://img.shields.io/github/issues/nazneenansari/Lead-Scoring-Pipeline)](https://github.com/nazneenansari/Lead-Scoring-Pipeline/issues)
[![Last Commit](https://img.shields.io/github/last-commit/nazneenansari/Lead-Scoring-Pipeline)](https://github.com/nazneenansari/Lead-Scoring-Pipeline/commits/main)

> 🚀 An end-to-end machine learning pipeline to score and prioritize leads efficiently — from raw data ingestion to model training and inference.

---

## 📋 Table of Contents

- [Why This Project](#why-this-project)
- [Features](#features)
- [Pipeline Flow Diagram](#pipeline-flow-diagram)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Example Usage](#example-usage)
- [Pipeline Details](#pipeline-details)
- [Running Tests](#running-tests)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 💡 Why This Project

Lead scoring helps sales and marketing teams focus on the most valuable prospects.  
This project automates that process using an organized and modular machine learning pipeline — ensuring scalability, reproducibility, and ease of maintenance.

It covers:
- Data ingestion and preprocessing  
- Automated training of ML models  
- Lead scoring inference  
- Model versioning and reproducibility  

---

## ✨ Features

✅ Modular pipeline architecture (data, training, inference)  
✅ Automated preprocessing and feature engineering  
✅ Configurable model training with logging  
✅ Scalable design for continuous integration/deployment  
✅ Comprehensive unit tests  

---

## 🔁 Pipeline Flow Diagram

```mermaid
flowchart TD
    A[Raw Lead Data] --> B[Data Pipeline]
    B --> C[Feature Engineering & Cleaning]
    C --> D[Training Pipeline]
    D --> E[Model Training & Validation]
    E --> F[Model Registry / Artifact Store]
    F --> G[Inference Pipeline]
    G --> H[Lead Scoring Output]
    H --> I[CRM / Dashboard Integration]

## 🗂 Repository Structure

Lead-Scoring-Pipeline/
├── Lead_scoring_data_pipeline/
│   ├── ingestion/
│   ├── preprocessing/
│   └── feature_engineering/
├── Lead_scoring_training_pipeline/
│   ├── model_training.py
│   ├── evaluation.py
│   └── utils/
├── Lead_scoring_inference_pipeline/
│   ├── load_model.py
│   ├── predict.py
│   └── output/
├── notebooks/
│   └── exploratory_data_analysis.ipynb
├── unit_test/
│   ├── test_data_pipeline.py
│   └── test_model_training.py
├── requirements.txt
├── LICENSE
└── README.md

