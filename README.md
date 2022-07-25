# Building-a-Book-Recommender-System
Building a Book recommender system using Popularity-based filtering, collaborative filtering and content-based filtering.

The datasets are from bookcrossing.com, a free online book club which was founded to encourage the practice of "leaving a book in a public place to be picked up and read by others, who then do likewise", aiming to "make the whole world a library." The dataset was collected during year 2004.

# What is a Recommender Sytem?
1. It is a subclass of information filtering, that seeks to predict the "rating" a user will give to an item, and basis these predicted ratings, recommends Top-N rated items to that /user
2. It helps users by suggesting them most relevant items from a large corpora.
3. In other words, it is a useful alternative to search algorithms, as they help users discover items they might not have found otherwise

# Why Recommender systems have become so important in today's online world?
1. Increases Revenue by directing the items and sales offers to specific users, and thus increasing the likelihood of selling items.
2. Increases Customer retention: It helps business in understanding the needs of customers & eventually, in devising the
right strategies to foster and maintain relationship with them.
3. Makes User’s life easier by handling a large amount of information and by provide them with personalized, exclusive content and service recommendations, which further leads to customer satisfaction

# Over-view of Book Recommender System built under this project:
<img width="684" alt="image" src="https://user-images.githubusercontent.com/100269915/180019627-dee1f241-f6de-450b-b9d0-16b3af3e6b95.png">

# Conclusions:
1. Majority of readers are from USA, followed by Canada.
2. The average of ratings given by Kids was the highest, followed by seniors; On average, rating given by readers from Spain & France were the highest.
3. For new users, built global popularity based recommender systems.
4. For registered users with no rating history, built demographics based popularity recommender systems.
5. For users with ratings history, built collaborative, content based and hybrid recommender systems.
5. For this dataset, Content-based recommender has the highest catalogue coverage for all N (as, ~43% for N=10), while Hybrid recommender system has the highest MAP@N for all N (as, MAP@10 = 2.43%).
