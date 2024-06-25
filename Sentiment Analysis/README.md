
## Project: Sentiment Analysis of Cryptocurrency-Related Tweets

**Description:**

This project leverages advanced natural language processing (NLP) techniques to analyze sentiment in cryptocurrency-related tweets. Two state-of-the-art transformer models, BERT and RoBERTa, are employed for sentiment classification. The project also includes a baseline Naive Bayes model for comparison.

**Key Objectives:**

*   Develop and evaluate high-performance sentiment analysis models for the cryptocurrency domain.
*   Investigate the effectiveness of different model architectures (BERT, RoBERTa, Naive Bayes) on social media text.
*   Explore potential applications in market analysis and trading strategies.

**Dataset:**

*   Open-source dataset of annotated cryptocurrency tweets.
*   Preprocessed and balanced for fair representation of positive, negative, and neutral sentiments.

**Methodology:**

1.  **Data Preprocessing:** Thorough cleaning of the dataset, including removal of irrelevant information, emojis, stopwords, entities, and hashtags.
2.  **Tokenization:** Conversion of cleaned text into numerical representations using BERT and RoBERTa tokenizers.
3.  **Model Building:**
    *   Fine-tuning of pre-trained BERT and RoBERTa models with classification heads.
    *   Implementation of a baseline Naive Bayes classifier for comparison.
4.  **Training and Evaluation:**  Training and validation of models, followed by evaluation on a test set.
5.  **Result Analysis:**  Comparison of model performance using classification reports and confusion matrices.

**Results:**

*   Both BERT and RoBERTa models achieved a macro average F1-score of 0.93, demonstrating strong performance in sentiment classification.

**Key Findings:**

*   Transformer-based models (BERT, RoBERTa) are highly effective for sentiment analysis of social media text in the cryptocurrency domain.
*   The results pave the way for further research into sentiment analysis and its potential applications in market analysis and trading strategies.

**Files:**

*   `Presentation.pdf`: Project overview.
*   `Sentiment Extraction on Social media texts related to Cryptocurrencies.ipynb`: Detailed analysis and code.
*   `tweet_extraction_api.ipynb`: Twitter API integration for data collection.
