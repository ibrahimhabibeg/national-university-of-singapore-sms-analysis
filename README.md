# National University of Singapore SMS Analysis Project

## Overview
This project involves analyzing a dataset from The National University of Singapore SMS Corpus. The dataset comprises thousands of text messages (SMS) mostly from Singaporeans and students attending the University. The analysis focuses on understanding the characteristics of these messages.

## Dataset Description
The dataset contains the following features:
- **id**: A unique identifier for every SMS.
- **Message**: The actual text of the SMS in natural language.
- **length**: The number of characters in the message.
- **country**: The country the sender is from.
- **Date**: The month and year the message was sent.


## Data Cleaning and Preprocessing
Dropped an unnamed column
- Created a new binary feature from_singapore to indicate messages from Singapore
- Preprocessed messages by converting to lowercase, tokenizing, removing stop words, punctuation, numbers, single characters, and non-alphabetic characters, and lemmatizing the remaining words
Text Analysis
- Created word clouds to visualize frequently used words and nouns
- Identified the most common noun phrases and verb phrases
- Sentiment Analysis
- Analyzed sentiment distribution by country, year, month, and season

## Key Findings

- Most messages are positive, followed by neutral messages.
- Messages from Singapore are more positive than those from other countries.
- The most common words include informal language and laughter indicators ("haha", "lol").
- Common verb phrases suggest a focus on daily activities ("go home", "go eat").
- Frequent mentions of time ("wat time", "next time") and social events ("new year", "happy birthday") highlight their importance.

## Dependencies
- pandas
- nltk
- matplotlib

## Running the Analysis

- Clone this repository.
- Install required libraries (pip install pandas nltk matplotlib).
- Ensure the clean_nus_sms.csv file is in the same directory.
- Run the Jupyter notebook.

## Acknowledgments

I would like to thank Codecademy for offering the Data Scientist: NLP Specialist Professional Certificate, which provided the foundation and guidance for this project.