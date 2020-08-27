# Named Entity Recognition (NER) using Deep Learning


Named-entity recognition (NER) is also known as entity identification, entity chunking and entity extraction. The objective is to identify entities like person names, organizations, locations etc. from unstructured text.

In this project, we will work with a dataset provided by kaggle. The dataset can be accessed from the kaggle link below: https://www.kaggle.com/abhinavwalia95/entity-annotated-corpus

The sample data has already been annotated and each word has been tagged with the relevant POS and NER tags. In this project we will focus on identifying NER tags. However, the approach of identifying POS or NER tags using previous annotated data using Deep Learning remains the same. Just a minor change in the code can be used for the POS tagging instead.

For modeling we'll use Deep Learning. It would be a simple model - a Bidirectional LSTM layer followed by a Dense layer. You'll see that even with such a basic model we can achieve an accuracy as high as almost 99%!
