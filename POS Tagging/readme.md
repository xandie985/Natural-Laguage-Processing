POS Tagging with Neural Networks: Project Summary

**Objective:**

Develop neural network models for Part-of-Speech (POS) tagging using GloVe embeddings and evaluate their performance on the dependency treebank dataset.

**Dataset:**

* Dependency Treebank: Contains sentences with words/symbols and corresponding POS tags.
* Split into train, validation, and test sets.

**Approach:**

1. **Data Preprocessing:** Cleaned and structured the dataset, handled out-of-vocabulary (OOV) terms using static embeddings.
2. **Model Building:**
    * Created a baseline model with a bidirectional LSTM layer and a dense layer.
    * Experimented with variations like GRU, additional LSTM layers, and additional dense layers.
3. **Training and Validation:** Trained models on the training set and evaluated them on the validation set using accuracy.
4. **Evaluation:** Selected the two best models based on validation performance and evaluated them on the test set using F1-macro score (excluding punctuation classes).
5. **Error Analysis:** Examined model errors and identified potential causes for improvement.

**Results:**

* Achieved promising results on the test set using the best performing model.

**Key Points:**

* Used GloVe embeddings as input features.
* Explored different neural architectures (LSTM, GRU, combinations).
* Followed a rigorous train-validation-test procedure for model selection and evaluation.
* Conducted error analysis to understand and address model weaknesses.

**Note:**

The specific performance metrics and error analysis details were not provided in the given information. However, the project followed a standard NLP workflow and demonstrated the application of neural networks for POS tagging.
