# NLP_legal_contracs_using_text_classification_sentment_analysis

## Business Understanding
- Intro to Contacts
Legal contacts are an essential part of every business that willing to comment any part of agreement. Contacts are very well written and structured to form a strong and precise set of conditions to be followed. Writing legal clauses require professionals and lawyers to construct the best way to specify a condition. In nature, human have intellectual thinking of designing a meaning of context from different perspective that achieve same goal. The idea of contracts is to create a mutual writing agreement between two parties that each can abide to the terms and conditions. If there is a business, there is a contract therefore we can imagine that there are tons of contracts has been written and millions of terms were included in legal documents to form a sophisticated set of order. Since human share a common sense of way to communicate and think, we can look more in-depth of how lawyers write their clauses and how similar it looks, how frequent the words used in, what is the important words that is included in clauses that is related to specific type of legal document.

- Contracts and NLP in-depth:
By allowing computer interactions, we can dig deeper to how we want to understand legal documents. We can use natural language processing (NLP) which is a subfield of linguistics and computer that is specializes in artificial intelligence to analyze textual big data. The process of analyzing texts can be segmented into supervised and unsupervised learning. Mostly, NLP aims to solve unsupervised learning that has far more challenges and complex structures. In this paper, I will explore some of the major and most recent implications of how to use NLP.

In order to deep dive into legal terms, the most fundamental questions are to understand NLP common practices when analyzing texts using NLP methodologies such as ‘term frequency’, ‘term frequency–inverse document frequency (Tf-idf)’, ‘word embedding’, and ‘sentiment analysis’

* Question 1: What are the most frequent terms in Legal Clause
* Question 2: Most Frequent Words By Clause Type
* Question 3: How Important a term to document? Using Tf-idf
* Question 4 :Can we find Relationship Between Legal Terms
* Question 5: How each Clause is explained based by topics.
* Question 6: Does Sentiment Analysis work best in Legal terms?

- Data Understanding
From this data, we will be using Frequency Analysis, TF/IDF Weighting, Bag of Words Classification, Word Embeddings, Skip-Gram/CBOW and Latent Dirichlet Allocation (LDA).

- Data
There are few ways to access legal document since they are more confidential, and most companies are conservative to expose these types of conditions. I found a source that is an open source for clauses examples to help lawyers pick any type of clauses and add it in contract

- Data Collection:
My data source is from LawInsider.com where I have collected over 21k legal clauses from 16 type of clauses that are related to ‘finance’. I used python using different type of libraries for scraping since the website keep blocking automated querying from the website, so I used selenium library to extract clause text and clause type.


- Data Overview
I only extract clause type and clause text to perform unsupervised analysis.


We can see from the above figure how the final data will look like and its ready to be analyzed and explore the business question we are interested in.

- Data Preparation
after we collected the data, the data need to be in a most suitable format and structure.

- Data Processing
The data needs to be cleaned and processed to be able to use our methods. In order to structure the data to our methods, we need to remove numbers, symbols and punctuations. I am using lemmatize method to clean text from the corpus.

- How To Run:
1. you can use rmd or jupter notebook
2. down load all files and run notebook
3. make sure to readd file path of R function file in the notebook