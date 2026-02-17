# Comparative NLP Analysis of U.S. Presidential Speeches (Obama vs. Trump)

## Overview

This project applies Natural Language Processing (NLP) techniques to compare linguistic patterns in official speeches by President Barack Obama and President Donald Trump.

Rather than relying on simple word clouds, this analysis investigates differences in grammatical framing, repetition, pronoun usage, and thematic emphasis using structured text analysis methods.

The goal is to identify how each president frames the American people, government responsibility, and national identity through language.

---

## Dataset

Speeches were obtained from publicly available transcripts:

- Barack Obama – Democratic National Convention Speech (2008)
- Donald Trump – Inaugural Address (2017)

Source dataset:
https://www.kaggle.com/datasets/littleotter/united-states-presidential-speeches

---

## Methods

### 1. Text Preprocessing
- Tokenization
- Lowercasing
- Stopword removal
- Punctuation filtering

### 2. Word Frequency Analysis
- Generated top-10 word frequency tables for each president
- Compared dominant vocabulary patterns
- Visualized frequency distributions using bar charts

### 3. Pronoun & Framing Analysis
- Examined usage of:
  - "I"
  - "We"
  - "Our"
- Identified rhetorical framing differences:
  - Individual action vs collective action

### 4. N-gram Analysis
- Extracted common bi-grams and tri-grams
- Identified repeated phrases:
  - Obama: "I will"
  - Trump: "we will"

### 5. Perspective & Tone Comparison
- Compared repetition patterns
- Evaluated audience targeting
- Assessed diction complexity differences

---

## Key Findings

- Obama frequently used first-person singular framing ("I will"), emphasizing personal leadership and policy commitments.
- Trump frequently used collective pronouns ("we will", "our"), emphasizing national unity and shared action.
- Trump's speech contained higher repetition density of campaign-style phrases.
- Obama's speech demonstrated higher lexical variety and more formal diction.
- Simple word clouds obscure structural rhetorical differences; grammatical framing reveals clearer contrasts.

---

## Tools Used

- Python (or R — replace with what you used)
- Pandas
- NLTK / spaCy / tidytext (replace with actual library used)
- Matplotlib / ggplot2
- Text preprocessing techniques
- N-gram extraction

---

## Visualizations

- Top 10 word frequency bar charts
- Pronoun comparison analysis
- Repeated phrase frequency charts

---

## Skills Demonstrated

- Text preprocessing
- NLP workflow
- Frequency analysis
- N-gram modeling
- Comparative dataset analysis
- Data visualization
- Analytical interpretation

---

## Project Structure

