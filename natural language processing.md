---
aliases:
  - NLP
---
converts unstructured text into structured text 

- unstructured -> structured: [[natural language understanding]]
- structured -> unstructured: natural language generation

# Use cases 
1. machine translation
2. virtual assistant
3. chatbot
4. [[sentiment analysis]]
5. spam detection

# Steps

1. lexical analysis 
	- [[tokenization]]
	- cleaning and feature extraction
		- [[lemmatization]]
		- [[stopword]] removal
		- correct misspelled words
2. syntactic analysis (parsing)
	1. interpret grammar structure
	2. subject, verb, object, etc.
	- simple [[neural network]]
3. semantic analysis
	1. understanding meaning on sentence and word levels
	2. defines sentence in context
	- [[transformer neural network]] (needs [[self-attention mechanism]], to assign meaning)
4. discourse integration
	1. integrates sentence meaning and conversation context
	- [[recurrent neural network|RNN]], [[long short-term memory|LSTM]]
5. pragmatic analysis
	1. social, legal, and cultural context
	2. interprets situation, identity and real-world knowledge
	3. (broader than discourse, but can also be included in it)
	- [[long short-term memory|LSTM]]