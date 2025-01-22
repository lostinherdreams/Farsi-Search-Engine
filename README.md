# Farsi Search Engine

## Overview
This project implements a search engine for Farsi text. It includes data preprocessing, positional indexing, and search query functionality.

## Features
- **Text Normalization**:
  - Handles Farsi-specific nuances, such as compound words, prefixes, diacritics, and Unicode replacements.
  - Removes unnecessary punctuation and converts English numbers to Farsi.
- **Stop Word Removal**:
  - Identifies and removes high-frequency, low-value words using frequency analysis.
  - Generates a report of removed stop words and their frequencies.
- **Stemming**:
  - Utilizes the Hazm library for Farsi word stemming.
- **Indexing**:
  - Creates a positional index to store term locations within documents.
- **Champion Lists**:
  - Implements efficient top-k retrieval mechanisms.
- **Query Search**:
  - Processes user queries and ranks results using TF-IDF (Term Frequency-Inverse Document Frequency).

## Dataset
The dataset is sourced from **Farsnews**, providing real-world Farsi text data for indexing and search functionality.  
> **Note**: The dataset is not included in the repository due to size and copyright considerations.


## Setup
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd farsi-search-engine
2. Install required packages:
   ```bash
   !pip install parsivar tqdm import_ipynb
3. Start querying:
   ```bash
   python search.py
