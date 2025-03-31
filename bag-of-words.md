# Tokenization

- create a set of [[token|tokens]] out of words
- remove punctuation and stopwords (and, the, for, is, etc) -> focus on meaningful words

# Vocabulary creation

- create a collection of unique words, assigning each an index

# Vectorization

- each document is represented as a [[vector]] of words, each coordinate corresponding to the frequency of a given word at a specific index


# Advantages
- simple 
- minimal [[pre-processing]]
- no need for grammar knowledge -> can be used across languages
- low computational complexity 
- can handle large datasets
- can be parallelized (deal with different segments of the text at the same time)

# Disadvantages
- no order information 
- no context
- resource intensive <- large corpora lead to high-dimensional vectors
- sensitive to irrelevant words (countered by disregarding stopwords)