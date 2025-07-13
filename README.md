'' This is guided movie recommendation project ''

It is a movie recommendation system . which use IMDB datasets . This is unfinished project as it is not deployed yet 
The dataset is also provided .
* It uses libraries like :
  numpy 
  pandas 
  porter stemmer - The Porter Stemmer is a widely used algorithm in Natural Language Processing (NLP) for reducing words to their root form, known as the stem
  stopwords  -The nltk.corpus.stopwords module in Python's Natural Language Toolkit (NLTK) provides a collection of common "stop words" across various languages.
             Stop words are frequently occurring words (like "the," "a," "is," "and") that often carry little semantic meaning and are typically removed during text processing in Natural Language Processing (NLP) tasks to focus on more significant terms.
  fidfVectorizer , CountVectorizer -CountVectorizer converts a collection of text documents into a matrix of token counts. It works on the "bag-of-words" model, where the order of words is disregarded, and only their frequency matters.
            fidfVectorizer stands for Term Frequency-Inverse Document Frequency. It extends CountVectorizer by not only considering the frequency of words within a document (Term Frequency - TF) but also their importance across the entire corpus (Inverse Document Frequency - IDF).
