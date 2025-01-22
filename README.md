# Farsi Search Engine

## Overview
This project implements a search engine for Farsi text. It includes data preprocessing, positional indexing, and search query functionality.

## Features
- Text normalization for Farsi, including handling compound words and prefixes.
- Positional index to store term locations within documents.
- Champion lists for efficient top-k retrieval.
- Search queries with ranking based on TF-IDF.

## Setup
1. Install required packages:
   ```bash
   !pip install parsivar tqdm import_ipynb