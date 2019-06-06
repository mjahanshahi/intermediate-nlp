# Intermediate Natural Language Processing:
## Real World Applications of Word Embeddings


### Schedule
 
#### Segment 1: Introduction to Language Models (Length: 30 min)

We will discuss:

- Complexity of natural language requires specific techniques:
- Language models are probability distributions over a sequence of words
- Key uses are in machine learning and unsupervised learning (search/IR and clustering/topic modeling)
- The intuition behind vector space modeling
- Description of some of the similarities and differences between different word embedding algorithms (word2vec, GloVe, PPMI)

#### Q&A / Break (Length: 10 min)

#### Segment 2:  Using Pretrained Word Embeddings (Length: 30 min)

We will demonstrate (using a Notebook):

- Ease of using pretrained embeddings
- Design considerations in using pretrained models including: noise, sentiments, generalization
- Some specific examples using different models (occupy in Twitter / Wikipedia / Common Crawl)
- Limitations using pretrained models:
  + Inputs: Implications of design decisions made during preprocessing on casing / stopwords / frequently occurring phrases
  + Output: Goal to learn similarity (example of word similarity tests)

#### Q&A / Break (Length: 10 min)

#### Segment 3: Training your own Word Embeddings (Length: 30 min)

We will discuss:

-	Optimizing for different outputs (semantic relations vs semantic similarity):
-	Preprocessing for outputs
-	Testing word embedding models (visual inspection, similarity pairs)

We will demonstrate:

-	Training a custom embedding model using spaCy to preprocess and the Gensim and scikit-learn API to train models

Note: Training an embedding can take many hours, so this notebook will focus on how to do it, and participants can continue to train or experiment in their own time.

#### Q&A / Break (Length: 10 min)

#### Segment 4: Applying Word Embeddings (Length: 40 min)

We will demonstrate:

-	Using word embeddings as inputs to understand documents
  + Supervised Machine Learning including Document Classification
  + Unsupervised Models including Document Clustering
  
We will discuss:

- Using word embeddings to extract insights from texts
  + Static vs Dynamic Embeddings on a high level
  + Hacking dynamic embeddings for other types of ordinal structure (grouping by reviews stars)

#### Q&A / Break (Length: 10 min)

