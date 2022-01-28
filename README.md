# Recommender Systems for Books, Transformers and GHG Emissions

This project is a proof of concept realised in order to obtain the diploma of **Data Scientist/Machine Learning Engineer** (*Openclassrooms* & *Centrale Supelec*).

The purposes of this project are multiples. First, this project try to prove that recommender engine can be used to suggest new books to users. Second, in this project, two categories of recommender engine was explored: Collaborative Filtering Algorithms and Content-Based Algorithms. Finally, an approach using new discoveries in NLP was tried. For each methods, an evaluation of GHG Emissions was realised.

Datasets used for this proof of concept can be downloaded on this page:  [Datasets from Kaggle](!https://www.kaggle.com/bahramjannesarr/goodreads-book-datasets-10m).

It exists an other dataset, but GoodReads dataset is more recent. 

## Exploration of the dataset

Analysis of datasets were splited in two parts: one about the books and one about the ratings/users. Description of books were processing alone. Text preprocessing needs a specific processing to be used in algorithms.

### Books Informations

- After cleaning and selecting, 140.000 books were selected. For each books, title, authors, publications' informations, average ratings, numbers of pages and description are presented.
- Preprocessing of descrition are realised in different steps : removing stopwords, special caracters and lemmatization. In order to simplify the preprocessing, only books written in English has been conserved.

![wordcloud_description](https://github.com/Sylvariane/Recommender_System_Books/blob/2f8840306d3899f4ee3ad8e77093d58b99b7118f/Illustrations/wordcloud.png)

### Ratings/Users Informations

Informations about the users is represented by the rating. At the beginning, ratings are explicit but are strings. A modification of the strings in to integer were realised. The ratings are between 1 to 5. After this transformation, the different datasets were merged in order to obtain more informations. 

![most_rated_books](https://github.com/Sylvariane/Recommender_System_Books/blob/2f8840306d3899f4ee3ad8e77093d58b99b7118f/Illustrations/most_rated_books.png)

## Modelisation

Recommendation algorithms are a vast domain. In this proof, we explore two kinds of algorithms: 
- Collaborative Filtering;
- Content-based Algorithms.

### Collaborative Filtering

### Content-based Algorithms

## GHG Emissions

![GHG Emissions Details](https://github.com/Sylvariane/Recommender_System_Books/blob/934ecfe8cfd3f93e450aa8a628d5ca672069a7dc/Illustrations/Emissions_Details.png)
with 0: SVD, 1: NMF, 2: KNN, 3: SlopeOne, 4: Co-Clustering, 5: KNN Basic, 6: KNN Means, 7: KNN Z Score, 8: KNN tunning

