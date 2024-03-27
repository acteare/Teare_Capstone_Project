# Sentiment Analysis of Top Songs by Year from the Billboard Hot 100 List

## Project Overview
The purpose of this project is to create a tool that can be used to identify the overall tone of a song through the sentiment analysis of its lyrics. The data used in this project comes from the Billboard Hot 100 List from 2000 - 2018. 

## Project Goal
Through the creation of the sentiment analysis tool, this project hopes to provide a relationship between popularity of a song and its tone. It hopes to determine if one specific mood will always deam more popular, or if the mood of popular songs changes with the current events of each year. 

## Project Prerequisits
- Git
- Jupyter Lab
- Python
- Microsoft Excel
- Microsfot Power Query
- Tableau

## Getting Started
1. Fork this repo into your GitHub.
1. Clone your repo down to your machine.
2. Install necessary libraries (found below)

## Necessary Libraries
- pandas
- matplotlib.pyplot
- numpy
- seaborn
- TextBlob
- re
- nltk
- word_tokenize from nltk.tokenize
- stopwords from nltk.corpus
- WordNetLemmatizer from nltk.stem

## Project Flow
1. Raw Data file (billboard_2000_2018_spotify_lyrics.csv) is cleaned and prepared using Microsoft Power Query from Excel
2. Cleaned file (clean_song_data.txt) is then put through the EDA python code for initial EDA.
3. Cleaned file (clean_song_data.txt) is run through tableau for additional EDA.
4. Cleaned file (clean_song_data.txt) is run through Sentiment_analysis_capstone.ipynb for sentiment analysis on song lyrics
5. Analyzed File (analyzed_data.txt) is again run through Microsoft Power Query from Excel for final prep before visualization
6. Analyzed File (analyzed_data.txt) is uploaded into Tableau for Visualization and final Analysis. 

## Project Files
**EDA.ipynb:** This file contains the code necessary to run the basic exploratory data analysis. This file is to be used after the intiial cleaning of the data using Microsoft Power Query from Excel

**Sentiment_analysis_capstone.ipynb:** This file contains the code necessary to run the sentiment analysis on the fully cleaned and analyzed data. This file takes in the data initally cleaned using Microsoft Power Query and produces a file that will undergo additional Microsoft Power Query transformation. 
