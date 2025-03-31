---
aliases:
  - NLP
---
1. lexical analysis 
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