# SentimentAnalyzerBERT
BERT stands for Bidirectional Encoder Representations from Transformers and it is a state-of-the-art machine learning model used for NLP tasks. 

There are two pre-trained general BERT variations: The base model is a 12-layer, 768-hidden, 12-heads, 110M parameter neural network architecture, whereas the large model is a 24-layer, 1024-hidden, 16-heads, 340M parameter neural network architecture.

We can easily load a pre-trained BERT from the Transformers library.

<h1> Sentiment Analysis with BERT </h1>
We take the following approach:

1. Install Transformers library;
2. Load the BERT Classifier and Tokenizer alıng with Input modules;
3. Download the IMDB Reviews Data and create a processed dataset (this will take several operations;
4. Configure the Loaded BERT model and Train for Fine-tuning
5. Make Predictions with the Fine-tuned Model
