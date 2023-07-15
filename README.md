# SentimentAnalysis

A Python application that performs sentiment analysis on a given paragraph using the Hugging Face Transformers library.

# Description

The Sentiment Analysis application is a Python program that analyzes the sentiment of a paragraph. It utilizes the Hugging Face Transformers library, specifically the "facebook/bart-large-mnli" model, to classify the sentiment of individual sentences within the paragraph. The application tokenizes the paragraph into sentences using the NLTK library and then applies the sentiment classification model to each sentence.

**Features**

> Sentiment Analysis: The application performs sentiment analysis on a given paragraph by classifying the sentiment of individual sentences within the paragraph using the Hugging Face Transformers library.

> Zero-shot Classification Model: The SentimentAnalysis class utilizes the "facebook/bart-large-mnli" model from the Hugging Face Transformers library. This model is pre-trained to classify sentences into various sentiment categories such as positive, negative, or neutral.

> Tabular Display of Results: The application presents the sentiment analysis results in a tabular format using the Pandas library. The results include the sentence, the assigned sentiment label, and the corresponding confidence score.

# Installation

**Clone the repository:**
https://github.com/AdopleAIOrg/SentimentAnalysis.git

**Install the required dependencies:**
pip install -r requirements.txt

# Usage

1. **Run the application:**
!streamlit run app.py & npx localtunnel --port 8501

2. Access the application by opening the provided URL in your web browser.

3. Enter the paragraph in the designated text area.

4. The application will perform sentiment analysis on the paragraph, classifying each sentence into a sentiment category (positive, negative, or neutral).

5. The results, including the sentence, sentiment label, and confidence score, will be displayed in a table.



