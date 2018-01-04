## Semantic Text-Matching
Given a corpus of question pairs, the task was to identify whether two questions were similar interms of their meaning. The dataset for this task was a part of the quora question pair challenge.

Ensemble based models (Random Forest and XGBoost) with 50 hand engineered features which included classical textmining features, Embedding features (Word2Vec and GloVe) and structural features (Tf-idf similarity measure, Page rank of each question) was compared against a Siamese version of LSTM (Long-short term memory) models. 

The highest accuracy among ML based model was found to be '0.81' compared to '0.845' on the Siamese LSTM.
