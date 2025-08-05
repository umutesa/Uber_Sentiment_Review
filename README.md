# Sentiment Analysis of 2024 Uber Customer Reviews

This project performs sentiment analysis on Uber customer reviews from 2024 using advanced Natural Language Processing (NLP) techniques and state-of-the-art deep learning models, I analyze customer feedback to gauge satisfaction levels, and derive actionable insights.

<img width="1813" height="920" alt="Screenshot from 2025-08-05 12-09-57" src="https://github.com/user-attachments/assets/958d207d-d212-4bcb-b540-ac239e462ad5" />


## Project Overview
The goal of this project is to explore Uber customer sentiment by:
- Preparing and cleaning a dataset of customer reviews.
- Applying text preprocessing techniques.
- Evaluating three NLP models: VADER, BERT, and BiLSTM.
- Extracting insights into customer satisfaction across various parameters.

## Dataset
The dataset contains thousands of customer reviews from Uber in 2024, including:
- User ratings
- Textual comments
- User Images
- User ID
- The number of likes per comment
- Date and time information regarding when the review was made

## Data Preprocessing
Preprocessing steps include:
- **Cleaning:** Removing noisy columns (e.g., user names, images, metadata) and filtering out incomplete reviews.
- **Normalization:** Converting text to lowercase and stripping punctuation.
- **HTML Tag Removal:** Removing any HTML artifacts.
- **Spelling Correction:** Correcting misspelled words.
- **Emoji Replacement:** Converting emojis into descriptive text (e.g., 😃 → "happy face").
- **Lemmatization:** Reducing words to their base forms.
- **Stop Word Removal:** Eliminating common words (e.g., "is," "the," "and") that do not contribute to sentiment.
- **Tokenization:** Breaking text into individual tokens.

## Models and Methods
I experimented with the following models:
1. **VADER (SentimentIntensityAnalyzer):**
   - A rule-based tool that outputs sentiment scores.
   - Very Fast
2. **BERT (Bidirectional Encoder Representations from Transformers):**
   - Excels at context-aware sentiment analysis.
   - Ideal for detecting irony and indirect complaints.
3. **BiLSTM (Bidirectional Long Short-Term Memory):**
   - Processes text in both directions to understand mixed sentiments.
   - Offers strong performance but has higher computational requirements.
