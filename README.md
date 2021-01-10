# paraphrase_detection

An exploration of neural methods and stacked models for classifying document pairs as paraphrases.

See `Paraphrase-Identification.pdf` for a thorough description of the methodology and results. The primary take away is that a stacked model combining a lean Siamese-LSTM with several engineered features into a Naive Bayes classifier achieved 90% accuracy on test data.

See `pipeline.py` for relevant code for all models.
