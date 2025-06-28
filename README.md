# Whatsapp-Chat-Analyser

An interactive Streamlit-based web app to perform insightful analysis on WhatsApp chat data. This project uses data cleaning, text processing, NLP, and data visualization techniques to uncover patterns like most active users, commonly used words, emoji usage, and more.

##Objective:
The main goal of this project is to analyze WhatsApp chat history (exported .txt file) and extract meaningful patterns from unstructured conversation data.

##Key Features

Upload .txt file exported from WhatsApp
Visualize:
Total messages, words, media shared
Active members and message frequency
Commonly used words (with WordCloud)
Emoji usage
Chat timeline and heatmaps
Works for both group and individual chats

##Techniques Used


1. Data Cleaning & Preprocessing
Parsed date, time, sender, and message from raw .txt files
Removed system-generated messages like "<Media omitted>"
Filtered empty or irrelevant lines

2. Text Processing
Tokenization of messages into words
Removed stopwords (e.g., "is", "the", "to")
Applied custom stopword filtering (e.g., removing "media", "omitted")
Extracted emoji characters using emoji module

3. Exploratory Data Analysis (EDA)
Counted total messages, words, and media
Calculated individual user contribution
Extracted most common words using Counter
Emoji frequency using Unicode-aware filtering

4. Data Visualization
Bar charts with matplotlib
Word cloud with wordcloud
Heatmaps for activity distribution (optional)
Interactive display using Streamlit


Live Demo:
https://whatsapp-chat-analyser-qyelml4xqf4hbgzsih2ql8.streamlit.app/

