# AI Strategy Signal Mining from Corporate Text

## Overview

This project develops a scalable natural language processing (NLP) pipeline to quantify artificial intelligence (AI) strategy signals from large corporate text sources.

Organizations communicate technological strategies through multiple channels, including regulatory filings and public communications. However, these signals are fragmented and difficult to quantify. This project converts large-scale unstructured text into structured firm-level indicators of AI adoption.

The pipeline was designed to support longitudinal business analysis and strategic intelligence modeling.

---

## Key Features

- Large-scale automated processing of corporate text documents
- Domain-specific AI dictionary engineering
- Word normalization per million words
- Multi-source signal generation
- Reproducible firm-year output structure

---

## Data Sources

This project integrates two complementary text sources:

### 1. 10-K Annual Reports (Internal Signals)

Output variable:

**AI_10K**

Definition:

Frequency of AI-related terms per million words in annual regulatory disclosures.

---

### 2. Corporate Newsroom Articles (External Signals)

Output variable:

**AI_News**

Definition:

Frequency of AI-related terms per million words in public-facing communications.

---

## Methods

### Dictionary Engineering

A domain-specific AI terminology dictionary was constructed using:

- Academic literature
- Industry terminology
- Iterative validation through sentence extraction

---

### Text Processing Pipeline

Core steps:

1. Load large-scale text files
2. Normalize and tokenize text
3. Match AI-related keywords
4. Count total word volume
5. Normalize frequencies
6. Generate firm-year indicators

---

## Example Workflow
Raw 10-K Text
↓
AI Dictionary Matching
↓
Word Normalization
↓
AI_10K Variable
↓
Firm-Year Dataset


---

## Output

Primary outputs:

- AI_10K
- AI_News
- Firm-year structured datasets

These outputs can be used in:

- Panel regression
- Time-series modeling
- Strategic trend analysis

---

## Business Applications

This pipeline supports:

- Competitive intelligence monitoring
- Detection of emerging technology adoption
- Cross-channel strategy analysis
- Technology investment research

---

## Tools & Libraries

- Python
- pandas
- numpy
- nltk
- regex
- file handling utilities

---

## Author

Jaewan Heo  
Hospitality Analytics | NLP | Panel Modeling


