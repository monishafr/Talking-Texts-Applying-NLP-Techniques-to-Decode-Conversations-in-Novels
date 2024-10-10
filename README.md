# Talking Texts: Applying NLP Techniques to Decode Conversations in Novels

## Project Overview
This project leverages Natural Language Processing (NLP) techniques to analyze and decode character dialogues in classic novels. By applying advanced NLP tools, we aim to understand how characters interact within these texts, explore dialogue patterns, and derive insights into the linguistic styles of different authors.

## Objectives
- To extract and analyze dialogues from two classic English novels using NLP.
- To identify and visualize the interactions between characters within these novels.
- To compare linguistic elements and dialogue styles across different texts.

## Data Sources
The novels used in this project are sourced from [Project Gutenberg](http://www.gutenberg.org/):
- **The Adventures of Sherlock Holmes** by Arthur Conan Doyle (Development text)
- **The Adventures of Tom Sawyer** by Mark Twain (Test text)

## Tools and Libraries Used
- **Python:** Primary programming language.
- **spaCy:** For tokenization, named entity recognition (NER), dependency parsing, and lemmatization.
- **NLTK:** Used for additional linguistic processing like stop word removal and text manipulation.
- **Pandas:** For data manipulation and analysis.
- **Matplotlib:** For visualizing data.

## Installation
To set up the project environment, run the following commands:
```bash
pip install spacy
pip install nltk
pip install pandas
pip install matplotlib

# Download the necessary spaCy model
python -m spacy download en_core_web_sm
