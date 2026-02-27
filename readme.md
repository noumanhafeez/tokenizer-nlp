# Tokenizer and N-Grams in Natural Language Processing (NLP)
# Tokenization is the process of converting raw text into smaller meaningful units called tokens.
# Tokens can be words, sentences, characters, or subwords depending on the task.
# Tokenization is the first and most important step in most NLP pipelines.
# Machine learning models cannot process raw text directly, so tokenization converts text into structured data.
# Word tokenization splits text into individual words based on spaces or punctuation.
# Sentence tokenization splits text into complete sentences.
# Character tokenization splits text into individual characters.
# Subword tokenization splits words into smaller meaningful units and is used in modern models like BERT and GPT.
# Lowercasing is commonly applied during tokenization to reduce vocabulary size.
# Removing punctuation is often part of text preprocessing before or during tokenization.
# Stopword removal can be applied after tokenization to remove common words like "the", "is", and "and".
# Stemming and lemmatization are additional preprocessing steps that may follow tokenization.
# An N-Gram is a sequence of N consecutive tokens in a text.
# A unigram is a single token.
# A bigram is a sequence of two consecutive tokens.
# A trigram is a sequence of three consecutive tokens.
# N-Grams help capture local context and word order information.
# Unigrams do not capture relationships between words.
# Bigrams capture relationships between adjacent words.
# Trigrams capture relationships between three consecutive words.
# N-Grams are widely used in language modeling.
# N-Grams are used in autocomplete systems to predict the next word.
# N-Grams are used in spell checking and grammar correction.
# N-Grams are used in speech recognition systems.
# N-Grams are used in sentiment analysis and text classification.
# Bigram probability is defined as P(w2 | w1) = Count(w1, w2) / Count(w1).
# Trigram probability is defined as P(w3 | w1, w2) = Count(w1, w2, w3) / Count(w1, w2).
# N-Gram models estimate the probability of a word given its previous words.
# N-Gram models are based on the Markov assumption.
# The Markov assumption states that the probability of a word depends only on a limited number of previous words.
# Data sparsity is a major problem in N-Gram models.
# Data sparsity occurs when many word combinations appear rarely or never in training data.
# Zero probability is a common issue when unseen word combinations occur.
# Smoothing techniques are used to handle zero probability problems.
# Laplace smoothing adds one to each count to avoid zero probabilities.
# Vocabulary size plays an important role in smoothing calculations.
# Higher order N-Grams require more memory and computational resources.
# Higher order N-Grams capture more context but increase sparsity.
# N-Gram models cannot capture long-range dependencies effectively.
# N-Gram models are simple and easy to implement.
# N-Gram models form the foundation of traditional statistical language modeling.
# Modern deep learning models like RNNs, LSTMs, and Transformers overcome many N-Gram limitations.
# Tokenization and N-Grams are essential concepts for understanding advanced NLP systems.
# A typical NLP workflow includes text collection, cleaning, tokenization, N-Gram generation, frequency counting, and probability calculation.
# Tokenization and N-Grams remain fundamental building blocks in natural language processing.