# Data Science Chatbot
<a href="https://colab.research.google.com/github/ilirjanahyseni/data-science-chatbot/blob/main/DataScience_Chatbot_with_Python.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


This repository contains a Python script for a chatbot that leverages web scraping and machine learning to answer user questions about Data Science. The chatbot dynamically fetches content from the [Data Science Wikipedia](https://en.wikipedia.org/wiki/Data_science) page and utilizes a mix of traditional Natural Language Processing (NLP) techniques and a machine learning model from [Hugging Face](https://huggingface.co/distilbert/distilbert-base-cased-distilled-squad) for question answering.

# Features
**Web Scraping**: Automatically retrieves the latest content from the Data Science Wikipedia page to ensure up-to-date information.
**Text Preprocessing**: Implements tokenization, lemmatization, and punctuation removal to clean and prepare text data for analysis.
**Response Generation**: Employs TF-IDF vectorization and cosine similarity to generate relevant responses to general user queries.
**Question Answering**: Integrates a pre-trained model from Hugging Face's Transformers library for answers to specific questions.
**Interactive Loop**: Maintains an interactive session with the user, providing informative responses until the session is terminated.

# Usage
To run the chatbot, execute the script in a Python environment. The chatbot will introduce itself and prompt the user to ask questions about Data Science, responding interactively based on the content fetched from Wikipedia and the inbuilt question-answering capabilities.

## Disclaimer and Acknowledgment
This project is created as an extension and adaptation of the knowledge acquired from the course "How to Build your own Chatbot using Python?" provided by [Great Learning](https://www.mygreatlearning.com/).
