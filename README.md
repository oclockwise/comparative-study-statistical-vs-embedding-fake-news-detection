# MBTI Personality Analysis (Singapore)

## Overview
This project analyzes MBTI personality types among Singaporeans using data from the 16Personalities website and Reddit. It explores personality distributions, trait patterns, and sentiment differences across the 16 MBTI types.

## Dataset
- Source: 16Personalities (Singapore profile) & Reddit API  
- Includes:
  - MBTI personality types (16 types)  
  - Trait distributions (I/E, S/N, F/T, J/P)  
  - Role groups (Analysts, Diplomats, Sentinels, Explorers)  
  - Reddit comments for sentiment analysis  

## Key Steps
- Web scraping (BeautifulSoup)  
- Data cleaning & preprocessing  
- Feature engineering (trait aggregation & normalization)  
- Sentiment analysis using NLTK  
- Data visualization (charts & word clouds)  

## Analysis Performed
- Distribution of MBTI types in Singapore  
- Comparison of Singapore vs global personality traits  
- Role group analysis (NF, NT, SJ, SP)  
- Sentiment analysis across MBTI types using Reddit data  
- Word frequency & word cloud analysis  

## Insights
- Singaporeans tend to be more Introverted, Feeling, and Perceiving  
- Diplomats (NF types) are the most common personality group  
- Sentiment varies across MBTI types (e.g. ESFP higher, ESTP lower)  
- Cultural and social factors influence personality trends  

## Tech Stack
Python, pandas, numpy, BeautifulSoup, NLTK, matplotlib, wordcloud, PRAW  

## Run
```bash
pip install pandas numpy matplotlib nltk wordcloud praw beautifulsoup4
jupyter notebook
