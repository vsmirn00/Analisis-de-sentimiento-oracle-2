### Sentiment Analysis with NLP, Topic Modelling and Deep Learning

This Jupyter Notebook was created for the second round of the Oracle League, held by Nuwe. The challenge consisted of performing Sentiment Analysis on a dataset using Natural Language Processing (NLP) tools. For this challenge Deep Neural Network with Transfer Learning was used.

### Dataset
The dataset used for this challenge was provided by Nuwe consisted of a raw text with the labels and the index. The goal was to predict whether a review was positive or negative based on the text content. The dataset was pre-processed and some additional features were added such as message length and the topic, which was modelled with LDA.

### NLP tools
The NLP tools used for this analysis included tokenization, stemming and stop-word removal. The text was pre-processed to remove punctuations, special characters and HTML tags.

### Topic Modelling
Topic Modelling with Latent Dirichlet Allocation (LDA) was used to identify the topics present in the customer reviews. The identified topics were then used as additional features in the dataset.

### Exploratory Data Analysis
Exploratory Data Analysis (EDA) techniques were used to gain insights into the dataset. The distribution of message lengths was evaluated and visualized to check out its distribution. On the other hand, using techniques such as T-SNE and PCA we could plot the patterns of the distribution of words.

### Deep Neural Network with Transfer Learning
A Deep Neural Network with Transfer Learning was used to train the model for Sentiment Analysis. The model was pre-trained on the GloVe embedding and then fine-tuned on the clean text with the features of topic and sentence length of words.

### Results
The final model achieved a high accuracy score on the test dataset, showing that the combination of NLP tools, Topic Modelling and Deep Learning with Transfer Learning can be effective for Sentiment Analysis.

### Conclusion
This project demonstrates the use of NLP tools and Deep Learning for Sentiment Analysis. The combination of these techniques can improve the accuracy of sentiment analysis models and provide valuable insights.
