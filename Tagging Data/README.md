# Tagging Data

In this folder first preprocessing and cleaning of the rss dataset has performed. In order to clean, we used ***NLTK*** and ***Spacy*** libraries, but found Spacy to be more efficient and updated package to have a shorter running time. This comparison is based on the performance for tokenization (20 times faster) and tagging (443 times faster) from this [article](https://towardsdatascience.com/hands-on-implementation-of-basic-nlp-techniques-nltk-or-spacy-687099e02816).

This step includes:

          * Convert text to lower case
          
          * remove stop words
          
          * lemmatization
          
Second, we implemented **POS** tagging using spacy. This step includes:

          * Tokeniziation
          
          * Frequency  
          
Third, we implemented **NER** tagging and displayed it using Spacy Display.

Finally we applied some statistical analysis to represent the frequency of POS tags and NER tags for one Json doc.
