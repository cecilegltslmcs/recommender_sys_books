# Recommender System for Books

This project is a proof of concept realised in order to obtain the diploma of **Data Scientist/Machine Learning Engineer** (*Openclassrooms* & *Centrale Supelec*).

The aim of this project is to used the recent advances in recommender system to books. 
There are many applications that using recommender algorithms such as Netflix, Youtube or Spotify but book's recommender system is less common. 
In order to realise this proof of concept, datasets coming from Goodreads API were used. 
The datasets were downloaded on this page : [Datasets from Kaggle](!https://www.kaggle.com/bahramjannesarr/goodreads-book-datasets-10m).

The first part of this project was cleaning and exploration of the datasets. This exploration was made in two parts:
- One part about tabular data (numerical and categorical data)
- One part about textual data (description text of books)

***

The second part of this project is about the modelisation. Recommender systems are multiples. Here, we decided to explorer four kinds of them:
- Simple recommender as we can see on IMBD
- User-based collaborative system (with SVD and KNN algorithms)
- Content-based system (with cosine similarity and transformers methods)
- Hybrid System.
For simple recommender and user-based collaborative system, the metric score is Root Mean Squared Error (RMSE). 
