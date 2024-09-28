# Machine-Learning-for-Texts

## Project Description

The Film Junky Union, an edgy community for classic movie enthusiasts, is developing a system to filter and categorize movie reviews. The objective is to train a model to automatically detect negative reviews using a dataset of IMDb movie reviews labeled by polarity. The model must achieve an F1 score of at least 0.85.

### Project Instructions

1. Load and preprocess the data.
2. Conduct exploratory data analysis (EDA) and assess class imbalance.
3. Prepare the data for modeling.
4. Train at least three different models on the training dataset.
5. Test the models on the testing dataset.
6. Create and classify a few of your own reviews using all models.
7. Analyze differences in testing results and provide explanations.
8. Present your findings.

**Note:** The project template includes code snippets for convenience, such as EDA visualizations, model evaluation routines, and BERT embeddings. You may modify the template as needed.

While logistic regression and gradient boosting are recommended for classification, you are welcome to explore other methods. BERT can be used, but keep in mind it requires significant computational resources and is best run on a GPU. If you choose to incorporate BERT, limit your dataset to a few hundred samples for efficiency.

### Data Description

The dataset is stored in `imdb_reviews.tsv` and was provided by Maas et al. (2011) for sentiment analysis. 

**Key Fields:**
- `review`: The review text
- `pos`: Target label ('0' for negative, '1' for positive)
- `ds_part`: 'train' or 'test' indicating the dataset partition

Explore additional fields in the dataset as desired.
