# Python Document Indexer
This is a simple document indexing program written in ```Python```. It uses:
* ```Cleaning```: Remove extra whitespace and punctuations.
* ```Stemming```: Uses the snowball stemmer (Porter2) from the ```nltk``` package, to stem the words.
before building a document-term index from which it builds the requisite ```inverse term-document``` index.
