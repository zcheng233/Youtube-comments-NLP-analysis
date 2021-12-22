# Youtube-comments-NLP-analysis

In this notebook, we have a dataset of user comments for youtube videos related to animals or pets. I will attempt to identify cat or dog owners based on these comments, find out the topics important to them, and then identify video creators with the most viewers that are cat or dog owners.

The dataset provided are comments for videos related to animals and/or pets. The dataset is 240MB compressed (647MB decompressed)

In this project, I completed the following steps:

Step 1: Identify Cat And Dog Owners
Find the users who are cat and/or dog owners.

Challenges: manually labeling on user-based vs comment-based.
Improvements: better labeling methods or get labeled data.
Step 2: Build And Evaluate Classifiers
Build classifiers for the cat and dog owners and measure the performance of the classifiers.

Challenges: modeling on comment-based labels; carefully split dataset; stratified sampling; word2vec embedding; classification model selection.
Improvements: try other classification methods; tuning relevant hyperparameters.
Step 3: Classify All The Users
Apply the cat/dog classifiers to all the users in the dataset. Estimate the fraction of all users who are cat/dog owners.

Challenges: majority vote to get user-based predictions; assumption and concern on dog/cat ownership status change.
Improvements: alternative assumptions and taking into accounts of status change.
Step 4: Extract Insights About Cat And Dog Owners
Find topics important to cat and dog owners.

Challenges: preprocessing methods; CounterVectorizer + IDF method to do TF-IDF in Spark; LDA fitting.
Improvements: more preprocessing methods; topic number selection; try other clustering methods; tuning relevant hyperparameters.
Step 5: Identify Creators With Cat And Dog Owners In The Audience
Find creators with the most cat and/or dog owners. Find creators with the highest statistically significant percentages of cat and/or dog owners.

Challenges: set reasonable ranking rule.
Improvements: more suitable ranking rules for specific use cases; considering statistically significant percentage.

