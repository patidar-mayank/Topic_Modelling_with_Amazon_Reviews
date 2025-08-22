# Topic Modelling with Amazon Reviews

This repository demonstrates topic modeling on Amazon product reviews using Python, NLP libraries, and LDA (Latent Dirichlet Allocation). The project walks through the process of data loading, preprocessing, topic modeling, and visualization.

## Overview

The goal of this project is to extract meaningful topics from a large collection of Amazon product reviews using Natural Language Processing (NLP) techniques and topic modeling algorithms. The pipeline includes the following steps:

1. **Data Loading:** Reading the Amazon reviews dataset.
2. **Text Preprocessing:** Cleaning, tokenizing, removing stopwords, and lemmatizing the text data.
3. **Topic Modeling:** Applying LDA to identify latent topics in the review texts.
4. **Visualization:** Using `pyLDAvis` to visualize the topics.

## Dataset

- The dataset used is `Reviews.csv`, which contains thousands of Amazon product reviews.
- Important columns:
  - `Text`: The full review text.
  - `Summary`: Short summary/title of the review.
  - `Score`: Rating given for the product.

**Note:** The dataset should be placed in the appropriate path as referenced in the notebook (e.g., `/content/Reviews.csv` for Colab).

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- nltk
- gensim
- spacy
- pyLDAvis

To install the required packages, run:

## Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/patidar-mayank/Topic_Modelling_with_Amazon_Reviews.git
    cd Topic_Modelling_with_Amazon_Reviews
    ```

2. **Install dependencies:**  
   See [Requirements](#requirements) section.

3. **Run the notebook:**
   Open `Topic_Modelling_with_Amazon_Reviews (1).ipynb` in Jupyter or Google Colab and run all cells sequentially.

## Results

The notebook prints out the top topics discovered in the reviews, along with the most relevant keywords for each topic. An interactive visualization is provided using `pyLDAvis` to explore the topics and their distributions across the corpus.
