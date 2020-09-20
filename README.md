# Extractive-Text-Summarization
Text Summarization is a problem identified in Natural Language Processing, which attempts to draw out the important information present in a large collection of unstructured textual data and output a summarized paragraph.
TextRank algorithm is an extractive and unsupervised text summarization technique. It is based on the PageRank algorithm developed by Google. In this algorithm, a matrix is generated of the probability of a user to move from one page to another.

Extractive summarization: It works by selecting the most meaningful sentences in an article and arranging them in a comprehensive manner. This means the summary sentences are extracted from the article without any modifications.

In TextRank, we form a cosine similarity matrix which stores the similarity scores of every sentence with one another. A graph is generated from the values obtained from this matrix , to calculate scores for each sentence in our dataset.

The vectorization is done by GloVe embeddings offered by Stanford University.

GloVe stands for Global Vectors for Word Representation. It is an unsupervised learning algorithm for obtaining vector representation of words. Training is performed on aggregated global word-to-word co-occurrence statistics from a corpus.
Algorithm of Text


for the steps ,please visit : https://medium.com/@itsmeishathakur/textsummarizer-using-textrank-and-glove-embeddings-59a229a98966
