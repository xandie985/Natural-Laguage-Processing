Fact Checking with NLP: Project Summary

**Objective:**

Develop a binary classification model to determine the veracity of claims (true or false) using supporting evidence from Wikipedia.

**Dataset:**

* FEVER: Contains claims, evidence sentences, and labels (SUPPORTS, REFUTES).
* Preprocessed to create (claim, evidence) pairs for classification.

**Approach:**

1. **Preprocessing:** Cleaned text data, removed stopwords, and handled special characters.
2. **Encoding:** Converted text to numerical representations using GloVe embeddings.
3. **Model Building:** Constructed a neural network model with LSTM layers for sentence embedding and a fully connected layer for classification.
4. **Training:** Fine-tuned the model using labeled training data.
5. **Evaluation:** Assessed model performance on validation and test sets using accuracy and F1-macro score.

**Results:**

* The model achieved a test accuracy of 49.21% and an F1-macro score of 0.3781. 

**Key Challenges:**

* Dataset imbalance: More "SUPPORTS" labels than "REFUTES".
* Limited vocabulary: Many out-of-vocabulary terms requiring special handling.
* Complex task:  Fact-checking requires understanding nuanced relationships between claims and evidence.
