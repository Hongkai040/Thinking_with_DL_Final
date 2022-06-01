# Gender disparity in the movie universe
This is the GitHub repository for final project of MACS 37000 Thinking with Deep Learing for Complex Social & Cultural Data Analysis. This project explores gender disparity in movie dialogs, movie character networks,  movie information, and movie reviews.  Movie dialogs are from the [Cornell Movie-Dialogs Corpus](https://convokit.cornell.edu/documentation/movie.html). Movie information and reviews were scraped from IMDb.

Group members: Hongkai Mao, Yu-Hsuan Chou, Zihe Yan, Taewon Min. 

### Folders :

####   movie_dialogs_text_analysis: 

1. `Movie_dialog_topic_modeling_word2vec.ipynb`: Uses topic modeling and word2vec models to explore the gender disparity in movie dialogs.   Contributors: Taewon Min, Hongkai Mao 
2. `Movie_dialog_text_generation.ipynb`: Fine-tunes GPT-2 using different types of movie conversations and dialogs to finish genderly-conjugate prompts. Contributor: Hongkai Mao

#### Movie_dialogs_network_analysis:

1. `Movie_dialog_network_metrics_analysis.ipynb`:Uses networknx to construct character networks to explore gender disparity in terms of network metrics. Contributor: Hongkai Mao
2. `Movie_dialog_deep_network_analysis.ipynb`: Uses GraphSAGE to explore disparity in terms of network embeddings. Contributor: Hongkai Mao

#### Movie_information_tabular_data_analysis:

1. `Movie_info_tabular_learning.ipynb`:Uses regression model and several neural network models to explore gender disparity in terms of audience preferences.  Contributor: Zihe Yan

#### Movie_reviews_sentiment_analysis:

1. `01_Movie_reviews_info_scraping.ipynb`: Scrapes movie reviews.  Contributor: Yu-Hsuan Chou

2. `02_Preprocess_Sentiment.ipynb`:Precprocessing for sentiment analysis.  Contributor: Yu-Hsuan Chou

3. `03_Sentiment_Analysis_IMDB50k.ipynb`: Fine-tunes BERT using the public-available IMDB 50k reviews dataset.  Contributor: Yu-Hsuan Chou

4. `04_Getting_Sentiments_from_Review.ipynb`:  Uses fine-tuned BERT to get sentiment of gender-related sentences from comments  extracted by using NER tagging.  Contributor: Yu-Hsuan Chou

5. `05_Visualization.ipynb`: Visualization of sentiment analysis results.  Contributor: Yu-Hsuan Chou

   

