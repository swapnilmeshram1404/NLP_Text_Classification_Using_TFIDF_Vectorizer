# SENTIMENT ANALYSIS USING TF-IDF VECTORIZER

> In this project we have performed sentiment analysis on movie review dataset 
using Text Classification using TF-IDF Vectorizer method.


## General Information

TF-IDF (Term Frequency-Inverse Document Frequency) Vectorizer is a common 
technique used in natural language processing (NLP) to convert text documents 
into numerical representations that can be used in machine learning algorithms.

TF-IDF Vectorizer calculates the importance of each word in a document by 
considering two factors: term frequency (TF) and inverse document frequency (IDF).

Term Frequency (TF): It measures the frequency of a word within a document. 
The assumption is that the more times a word appears in a document, the more 
important it is.

Inverse Document Frequency (IDF): It measures the rarity or uniqueness of a 
word across the entire document collection. Words that appear in many documents 
are considered less informative, while words that appear in only a few documents 
are considered more valuable. IDF is calculated as the logarithm of the total 
number of documents divided by the number of documents that contain the word.

The TF-IDF Vectorizer combines these two factors to assign a numerical value 
to each word in a document. The resulting vector represents the document in 
high-dimensional space, where each dimension corresponds to a word, and the 
value in each dimension reflects the importance of that word in the document.

The TF-IDF Vectorizer calculates the TF-IDF score for each word in each 
document, and it outputs a matrix where each row represents a document, and 
each column represents a word. This matrix can be used as input to machine 
learning algorithms for tasks such as text classification, clustering, or 
information retrieval.

In summary, the TF-IDF Vectorizer converts text documents into numerical 
vectors by considering the term frequency and inverse document frequency 
of each word. This representation allows machine learning algorithms to 
process and analyze text data effectively.
