# OpenA Text Analysis

# Scripts Overview

This repository contains three scripts that work with qualitative data. The scripts perform various operations using OpenAI's GPT-3 API for sentiment analysis, topic classification, and data summarization. Below are descriptions of each script:

## Script 1: Sentiment Analysis

### Functionality
This script:
- Loads a dataset and pre-processes the data, including tokenizing and exploding sentences.
- Utilizes OpenAI's GPT-3 API to classify the sentiment of each sentence as Positive, Neutral, or Negative.
- Outputs the results to `data_sentiment.xlsx` and `data_sentiment.csv`.

### Dependencies
- openai
- nltk
- pandas
- numpy
- os

### How to use
1. Set up your OpenAI API key.
2. Update the file path in the `pd.read_csv()` function to point to your dataset.
3. Run the script to get the sentiment of each sentence.

---

## Script 2: Topic Classification

### Functionality
This script:
- Loads a dataset and defines potential topics for various questions.
- Tokenizes sentences and processes the data for topic analysis.
- Utilizes OpenAI's GPT-3 API to classify the main topic of each sentence based on predefined topics.
- Outputs the results to `data_topics.xlsx` and `data_topics.csv`.

### Dependencies
- openai
- nltk
- pandas
- numpy
- os

### How to use
1. Set up your OpenAI API key.
2. Update the file path in the `pd.read_csv()` function to point to your dataset.
3. Modify the predefined topics as necessary.
4. Run the script to classify sentences into specific topics.

---

## Script 3: Data Summarization

### Functionality
This script:
- Loads two datasets and tokenizes sentences for summarization.
- Utilizes OpenAI's GPT-3 API to extract the most representative quotes from the dataset.
- Provides a detailed analysis of the data using the GPT-3 API.
- Merges the outputs of quotes and summaries.
- Outputs the combined results to `merged_output.xlsx` and `merged_output.csv`.

### Dependencies
- openai
- nltk
- pandas
- numpy
- os

### How to use
1. Set up your OpenAI API key.
2. Update the file paths in the `pd.read_csv()` functions to point to your datasets.
3. Run the script to extract representative quotes and get a detailed analysis of your data.

---

### Note
Before executing any script, ensure all dependencies are installed and datasets are located in the appropriate directory. Ensure you have a valid OpenAI API key. Always check API usage costs when using cloud-based APIs like OpenAI's GPT-3.
