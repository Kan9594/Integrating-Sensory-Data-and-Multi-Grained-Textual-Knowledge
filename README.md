# Integrating Sensory Data and Multi-Grained Textual Knowledge for Industrial Fault Diagnosis

This repository contains supplementary materials for our manuscript **"Integrating Sensory Data and Multi-Grained Textual Knowledge for Industrial Fault Diagnosis"**.

## 📦 Repository Contents

This repository provides:
- **Dataset Description** – Comprehensive documentation of the dataset construction, sensor specifications, and annotation guidelines
- **Sample Data Example** – A single JSONL example demonstrating the data format and structure

## 📊 Dataset Information

### Sample Data Format
We provide a sample data instance to illustrate the expected input format:

```jsonl
{
  "data": [...],        # Time-series sensor measurements
  "Fine_Grained_Description": "string",       # Fine-Grained Textual description
  "Coarse_I": "string",    # Coarse-Grained Textual description (Level-1)
  "Coarse_II": "string",      # Coarse-Grained Textual description (Level-2)
}

The full dataset will be released after the acceptance.
