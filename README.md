# Biomedical Literature Mapping and Analysis


## Overview

This project aims to map and analyze bibliographic data of biomedical literature related to Sudan. The goal is to simplify the navigation of extensive biomedical research and provide insights into trends and networks within this domain. Currently, the project focuses on developing a robust backend for various NLP tasks, with plans to create a user-friendly front end in the future.

## Motivation

With the increasing volume of unstructured text data, there is a growing need for efficient text analysis tools. Existing libraries often lack comprehensive functionality or have steep learning curves. This project addresses these issues by integrating essential NLP tools into a single, user-friendly package, designed to streamline the NLP workflow for researchers and developers.

## Features

### Text Preprocessing

- **Tokenization:** Splits text into individual tokens (words, phrases, etc.).
- **Stop Word Removal:** Eliminates common words that do not contribute to meaningful analysis.
- **Stemming and Lemmatization:** Reduces words to their base or root form for standardized analysis.

### Feature Extraction

- **TF-IDF (Term Frequency-Inverse Document Frequency):** Measures the importance of a term in a document relative to the entire corpus.
- **N-grams:** Extracts contiguous sequences of n items from text, providing context beyond individual words.
- **Bag of Words:** Converts text into a set of words without considering grammar and word order, useful for text classification.
- **LDA (Latent Dirichlet Allocation):** Discovers hidden topics in a corpus, allowing for topic modeling and trend analysis.

### Visualization Tools

![Word Cloud Example]([![photo_2024-07-31_06-23-42]](https://github.com/RehamJamal13/cognitive-network-analysis-and-topic-modelling-for-bibliography-literature-of-sudan-/issues/1#issue-2439234850))

- **Word Cloud Generation:** Visualizes the most frequent terms in a corpus.
- **Network Graphs:** Displays relationships between words or topics, enhancing interpretability.

![Network Graph Example](path/to/networkgraph.png)

### Model Training and Evaluation

- Interfaces for training and evaluating models for tasks such as sentiment analysis and text classification.
- Utilizes metrics like precision, recall, and F1-score to assess model performance.

## Future Work

While the current focus is on building a robust backend, future plans include developing a user-friendly front end to make the tools more accessible and intuitive for users.

## Impact

The project has been widely embraced in both academic and industry settings. Its comprehensive functionality significantly reduces the time and effort required for text preprocessing, feature extraction, model training, and evaluation. By enhancing productivity and enabling more effective text analysis, this project serves as a valuable resource for researchers and developers.

## Installation

To install the necessary dependencies, run:

```bash
pip install -r requirements.txt

