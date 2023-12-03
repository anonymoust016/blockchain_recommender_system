# Blockchain Recommender Systems using Blockchain Data (Under Review)

![Blockchain Recommender Methods](https://github.com/anonymoust016/blockchain_recommender_system/blob/main/Fig/recommender_methods.png)
**Abstract:**
While there has been extensive research in designing recommender systems for centralized applications, blockchain recommender systems remain under-explored. To fill this gap, we investigate collaborative filtering (CF), a popular recommendation approach that captures similarities among users in terms of their transaction histories. For example, if two users liked movies $a$, $b$ and $c$, and the first user additionally liked movie $d$, then CF may suggest movie $d$ to the second user.  We show how to identify similar smart contracts to enable richer recommendations, akin to recommending movie $e$ in the above example if it features similar actors as $d$.  Using Ethereum transaction data, we test two CF methods: a simple and fast Matrix Factorization algorithm and a state-of-the-art method for recommender systems based on Graph Neural Networks (GNNs).  Our results show that GNN outputs effective recommendations, at the expense of latency.

## How to Run the Project

Follow these steps to set up and run the project:

### 1. Unzipping the Dataset

Begin by unzipping the dataset into the root directory. Use the following command in your terminal:

```bash
unzip dataset.zip -d dataset
```

### 2. Running the Notebook

After unzipping the dataset, proceed to run the Jupyter notebook:

- Open the `GNN-recommender-pyg.py` notebook in your Jupyter environment.
- Execute the code blocks in the notebook sequentially, starting from the top and proceeding to the bottom.
