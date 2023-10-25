# Recommender-System-and-ConvAI-using-LLMs-on-e-commerce-Data

# **Project Summary:**
We'll use amazon's data for our project. You can either download data directly from [Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset), or  you can donwload using Kaggle's API.
The idea of the project is to build a Recommender System, and implement a Conversation AI for different tasks ( explained below).

# Recommender System using cosine and jaccard similarity:
  * Product Clustering: We'll use product_id, Discounted_Price, Subcategory, rating to find products similarity.
  * User clustering: Calculate users similarity using jaccard similarity with input features such as user_id, product_id, Subcategory, rating.

# Conversational AI using LLMs:

  * Sentiment Analysis: We'll do sentiment analysis using BERT Model.
  * Generate Questions: We'll generate 4 questions per record that users could potentially ask to Virtual Assistant.
  * Answers users' questions: We'll use OpenAI's davinci engine to answer each question that users could potentially ask.
  * Summarize Product Description: We'll use t5-small model from Google to summarize product using product description  to users.




