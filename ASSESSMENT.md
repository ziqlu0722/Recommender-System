**1. If there's very limited user interaction data, which recommender approach might be used?** (choose all that apply)

    A. Item-based Collaborative Filtering
    B. Content-based Filtering
    C. Hybrid Recommender that combines Popularity Recommender, Content-based Ciltering and Collaborative Filtering
    D. Deep-learning-based Collaborative Filtering

    (Solution: B, C)

**2. What can be used to evaluate a recommender system?** (choose all that apply)

    A. Precision@N 
    B. Recall@N 
    C. MAE
    D. MSE

    (Solution: All)

**3. Which of the following are true of Collaborative Filtering System?** (choose all that apply)

    A. Even if each user has rated only few items, you can still build a CF recommender. 
    B. To build a CF recommender, you need users to rate all items in your training set. 
    C. For CF recommender, it is possible to use optimization algorithms to train the dataset. 
    D. To use CF, you need to manually design a feature vector for every item in your dataset.

    (Solution: A, C)

    *Note: this question is adapted from [Coursera](https://www.coursera.org/learn/machine-learning/exam/3HGvu/recommender-systems)

**4. What approach can be used to measure similarity of item/user vector?** (choose all that apply)

    A. Cosine
    B. Pearson Correlation
    C. Dot Product
    D. Euclidean distance

    (Solution: All)

**5. Can you explain how does a matrix factorization based collaborative filtering works?**

    (
     Solution:
     1: MF assumes there exists a low dimensional latent feature space to represent item and user.
     2: MF decomposes the user-item interaction matrix into the product of lower dimensional user-feature matrix and item-feature matrix.
     3: MF reformulats recommendation problem as an optimization problem - how good we are in predicting the rating.
     )