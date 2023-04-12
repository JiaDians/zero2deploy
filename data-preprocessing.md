# Data Preprocessing
Why preprocessing ?
- Incomplete: Data lacks attributes or containing missing values.
- Noisy: Data contains erroneous records or outliers.
- Inconsistent: Data contains conflicting records or discrepancies.
- Make the data into a format and type acceptable to the Model.

Word Embedding
- OneHotEncoding: Represent vocabulary as an N-dimensional vector, N = the number of all vocabularies
  - eg:'king'= [1,0,0...,0], 'queen'=[0,1,0...,0],...
  - Advantages: simple and clear
  - Disadvantages: waste of space, unable to show the relationship between words
- Word2Vec: Represent vocabulary as an K-dimensional vector, K is a arbitrary number
  - 'king'=[-0.95,0.93,0.7,...,0], 'queen'=[0.97,0.95,0.69,...,0],...
  - Advantages: low dimensionality, can show the association between words
  - Disadvantages: hard to explain
# Task
- Preprocessing and label your data.
