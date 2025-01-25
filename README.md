# README

## Project Title
Bluesky Migration: User Perceptions and Motivations

## Overview
This project is the final work for the Python coding module in the MA Digital Humanities program at King's College London. 
It explores why users migrated from X (formerly Twitter) to Bluesky during the US election and examines user perceptions and key motivations behind this shift.

## Research Question
- How do Bluesky users perceive their migration?
- What are the main reasons and patterns driving this move?

## Methodology
### Data Collection
Posts containing "left X" were collected from Bluesky using the "top" sorting option to prioritize highly engaged content. Only English-language posts were included. Data scraping was done with the BlueSkyScraper GitHub project and modified to capture timestamps. Selenium WebDriver handled extraction, and Pandas was used for data processing. In total, 8,265 posts were gathered between December 9 and December 10, 2024 (UK time).

### Data Analysis
1. **Timeline Analysis**: Matplotlib visualized post frequency over time, with key dates marked.
2. **Textual Analysis**: 
   - Stopwords were removed using NLTK.
   - Word frequency was analyzed with collections.Counter, excluding common and topic-specific words.
   - SpaCy tagged parts of speech.
   - A word cloud was generated using the WordCloud library, highlighting key adjectives and nouns.

## Contact
billow0612@gmail.com, Annie Wan

