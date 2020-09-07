# Tales from the Crypto

![crypto_currencies](Images/crypto.jpg)

*This repository contains the Unit 12 Natural Learning Processes homework assignment, "Tales from the Crypto"  in the FinTech bootcamp course at the University of Toronto's School of Continuing Studies.*

---

## Table of Contents

- [Project Description](#Project-Objectives)
- [Project Conclusions](#Project-Conclusions)
- [Installation Requirements](#Installation-Requirements)
- [File Contents](#File-Contents)

---

## Project Objectives

The following assignment seeks to apply the natural learning process (NLP) to understand the sentitment in the latest news articles related to Cryptocurrency featuring coins such as; Bitcoin and Ethereum. Using NLP fundamental techniques will help better understand other relevant factors involved with coin prices such as; common words, phrases, organizations, and entities mentioned in the selected articles. 

### Part 1: Sentiment Analysis

Part one of the homework assignment utilizes the [News API Client](https://newsapi.org/), to pull the latest articles featuring Bitcoin and Ethereum to conduct a sentiment analysis. Additionally, a DataFrame is created to capture the sentiment scores for each coin and respond to analysis questions. 

### Part 2: Natural Learning Process

This section of the assignmnet uses NLTK and Python processes to tokenize text, find Ngrams, and create word clouds for Bitcoin and Ethereum. 

**Processes Utilized in Part 2:**

- Tokenize
- Ngrams and Word Frequency Analysis
- Word Clouds

**Bitcoin Word Cloud:**

![btc_wc](Images/bitcoin_wc.png)

**Ethereum Word Cloud:**

![eth_wc](Images/eth_wc.png)

### Part 3: Named Entity Recognition

Using Spacy, this section builds a named entity recognition model for Bitcoin and Ethereum.

**Bitcoin NER:**

![btc_ner](Images/bitcoin_ner.png)

**Ethereum NER:**
![eth_ner](Images/ethereum_ner.png)

---

## Project Conclusions 

### Sentiment Analysis Results

The following three questions regarding mean score, compound score, and positive score are based on the descriptive statistics conncluded in [Part 1: Sentiment Analysis in the Unit 12 - Tales of the Crypto Notebook](Unit_12_Tales_from_the_Crypto_Notebook.ipynb)

#### Questions:

**Q: Which coin had the highest mean positive score?**

A: The coin with the highest mean positive score is **Ethereum** with a mean positive score of 0.691. Verses Bitcoin, with a positive mean score of 0.684. 

**Q: Which coin had the highest compound score?**

A: The coin with the highest compound score is **Ethereum** with a max compound score of 0.851. Verses Bitcoin with a max compound score of 0.750.

**Q. Which coin had the highest positive score?**

A: The coin with the highest positive score is **Ethereum** with a max positive score of 0.311. Verses Bitcoin with a max positive score of 0.198. 

---

## Installation Requirements

To successfully view the [Unit 12 - Tales of the Crypto Notebook](Unit_12_Tales_from_the_Crypto_Notebook.ipynb), the following installations are required: 

```
pip install pandas
pip install nltk
pip install Counter
pip install matplotlib
pip install -U spacy
```

Additionally, the user must create a local *.env* file containing their personal News API Client keys to successfully pull the approporaite articles from the API. 

---




