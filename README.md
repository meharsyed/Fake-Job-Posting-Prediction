# Fake-Job-Posting-Prediction

**Detecting Real/Fake job postings using pre-trained BERT Model**

It's a fake/real job posting prediction project and the available dataset consists of 17880 job postings. To detect real/ fake job postings, the dataset is first pre-processed and then passed from a pipeline to get the embedding and tokenizations of the input text features before passing them to the input model for the training process.

The preprocessed Dataset is then split into train, validation, and testing datasets with a 70:10:20 ratio. (Keep in mind the Class balance splitting of the dataset).

A pre-trained Transformer model named *BERT( (Bidirectional Encoder Representations from Transformers)* is a popular natural language processing (NLP) model, is used to train the model and it can classify the preprocessed splitted training dataset into Real/ Fake classes.

The model is evaluated on the testing dataset as well as the unseen dataset to visualize the model performance in the form of confusion matric and heatmap.

The dataset is publically available on the given link:

https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction
