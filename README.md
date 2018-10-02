# Basic Movie Recommender System

This is a basic content-based recommender system for movies.

## Recommender Systems

Recommender systems are used to predict the _rating_ or _preference_ that a user would give to an item. This is commonly used to recommend or to suggest products, and other items such as movies, restaurants, friends on social media, music, and etc. to the users.

Broadly speaking, the recommender systems can be classified into 4 types:

* __Simple Recommernders__: which offer generalized recommendations to all the users based on some features of the item. The basic idea behind this system is that most popular items have a higher probability of being liked by an average user.

* __Content-Based Recommenders__: which suggest similar items based on a particular item using the item's metadata. The idea is that a person who liked a specific item would also like similar items.

* __Collaborative Filtering (CF) Engines__: these try to predict the rating or preference that a user would give an item, based on past ratings and preferences of other users. In other words, this method uses the _wisdom of the crowd_ to recommend items. These engines do not need the item meta-data.

* __Hybrid Recommender Systems__: Combining content-based and CF approaches can be more effective in some cases. Hybrid approaches use different techniques for this combinations, such as making predictions separately using each approach and combining the results, adding content-based capabilities to the CF, or by unifying the approaches in one model.

In general the CF approach is more commonly used as it usually gives better results and is relatively easy to understand. The algorithms is able to do feature learning on it own and to learn what features to use.

CF can be devided into:
* __Memory-Based Collaborative Filtering__: This approach uses user rating data to compute the similarity between the users or items. Commonly, _Pearson correlation_ nad _vector cosine_ based similarity measures are used. 
* __Model-Based Collaborative Filtering__: In this approach models are developed using different data mining, machine learning algorithms to predict users' rating of unrated items. Model-based CF algorithms can be _Bayesian Networks_, _Clustering Models_, _Latent Semantic Analysis_ such as, _singular value decomposition_, _probabilistic latent semantic analysis_ and etc.

To get more theoretical details on recommender systems, one of the recommended textbooks is: _Recommender systems by Jannach and Zanker_.

The sources used to create this tutorial are the following:

* Udemy's course Python for Data Science and Machine Learning Bootcamp.
