# Movie-Recommendation-on-IMDB-Dataset
The dataset is IMDB top 250 English movies, it can be downloaded from: https://data.world/studentoflife/imdb-top-250-lists-and-5000-or-so-data-records.  
In this dataset there are 250 movies (rows) and 38 attributes (columns).  
I have used *Rapid Automatic Keyword Extraction* (RAKE) library, it is a domain independent keyword extraction algorithm which tries to determine key phrases in a body of text by analyzing the frequency of word appearance and its co-occurance with other words in the text.  
This project is *Content-based Recommender* Using Natural Language Processing (NLP).  
Strategy:   
Count Vectorizer + Cosine Similarity
- *Count Vectorizer* : for converting sentences into vectors
- *Cosine Similarity* : calculates similarity by measuring the cosine of angle between two vectors. 
