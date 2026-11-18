### Fake News Detection using BERT

I developed an NLP-based Fake News Detection system using the BERT pretrained Transformer model. The objective of the project is to classify news articles as REAL or FAKE based on their textual content.

I used the Fake and Real News Dataset containing labeled news articles. I performed data inspection, preprocessing, duplicate removal, and train/test splitting. I used the BERT tokenizer to convert the news text into input IDs and attention masks.

I loaded the pretrained BERT Base Uncased model with a sequence classification head and fine-tuned it on the news dataset using PyTorch and Hugging Face Transformers.

I evaluated the model using accuracy, precision, recall, F1-score, and a confusion matrix. I also implemented predictions for new news articles, saved the trained model and tokenizer, and created a Flask REST API to serve predictions.

**Technologies:** Python, NLP, BERT, PyTorch, Hugging Face Transformers, Pandas, Scikit-learn, Google Colab, Flask, REST API.
