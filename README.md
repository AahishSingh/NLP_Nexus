# NLP Nexus
NLP Nexus is a tool designed to streamline text analysis and document summarization using advanced Natural Language Processing (NLP) techniques. It enables you to quickly generate summaries, perform sentiment analysis, and visualize text data, making it easier to digest and understand large volumes of information.

## Features:

- **Text Summarization:** Generate concise summaries of documents, extracting key information for quick comprehension.
- **Sentiment Analysis:** Assess the sentiment expressed in the text, whether it’s positive, negative, or neutral.
- **Document Management:** Upload and organize your documents for efficient analysis and summarization.
- **Word Cloud Generation:** Visualize frequently occurring words in your text to gain a quick overview of key themes.
## Usage:

- **Text Summarization:** Upload your document or paste the text into NLP Nexus. The tool will then generate a summary for you.
- **Sentiment Analysis:** After uploading your document, NLP Nexus will analyze the sentiment expressed in the text and provide detailed insights.
- **Document Management:** Use the document management feature to upload, organize, and manage your documents for seamless analysis.
- **Word Cloud Generation:** Utilize the word cloud feature to visually identify and explore the most common words in your text.
## Requirements:

- **Modules:** Spacy, NLTK, Flask, TextBlob, NumPy, Scikit-Learn, PyPDF2
- **Python Version:** 3.10 - 3.11
## Installation:
- python -m nltk.downloader punkt
- python -m nltk.downloader stopwords
- python -m nltk.downloader vader_lexicon
- pip install -r requirements.txt
## Running Application:
- python app.py
