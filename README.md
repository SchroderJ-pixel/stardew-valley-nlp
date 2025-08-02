# Web Mining and Applied NLP (44-620)

### Mod 7: Final Project — Article Summarizer  
**Name:** Justin Schroder  
**Date:** 8/2/2025
**GitHub Link:** [https://github.com/SchroderJ-pixel](https://github.com/SchroderJ-pixel)

---

## 📄 Project Overview

This project focuses on natural language processing techniques to summarize a web article. It walks through the full pipeline — from scraping and parsing the article's HTML to analyzing sentiment, lemmatizing content, and generating summary sentences based on polarity scores.

The goal was to create two separate summaries:
- One using token-based sentiment analysis
- One using lemma-based sentiment analysis

Both were compared to the original article in terms of sentiment and content quality.

---

## 🧠 Key Concepts Used

- Web scraping with **BeautifulSoup**
- Sentiment analysis using **spaCyTextBlob**
- Tokenization and **lemmatization** via **spaCy**
- Frequency analysis with **Counter**
- Data visualization with **matplotlib**
- Summary generation using **sentiment-based filtering**

---

## 📊 Summary of Findings

- The original article had a fairly neutral tone with a polarity score around `0.06`.
- Both summaries had higher polarity scores (~0.33–0.34), since they focused on more emotionally expressive or positive sentences.
- The **token-based summary** felt more natural and closer to the article’s original flow, while the **lemma-based version** sometimes lost nuance.

---

## 📌 Final Thoughts

This project was a great hands-on way to apply real-world NLP techniques and see how even small preprocessing steps (like lemmatization) can impact results. It also reinforced how important sentence selection is when trying to summarize longer content accurately and clearly.


# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt
