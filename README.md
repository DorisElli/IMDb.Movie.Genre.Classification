
# IMDb Movie Genre Classification Using Plot Summary
This project focuses on the task of classifying movie genres using natural language processing techniques. The motivation behind this research is the need for precise and effective movie genre classification, with potential applications in marketing and movie recommendation systems. IMDb, a well-known source of movie information, serves as the primary data source.

# Background
Various approaches have been explored in prior research to classify movie genres based on features such as plot summaries, scripts, or viewer reactions. This project leverages advanced NLP techniques, particularly the DistilBERT transformer model, for more accurate genre classification.

# Methodology
The methodology involves preparing the dataset, tokenizing text data, and employing DistilBERT and a count-based baseline model for classification. The hyperparameters and training process are fine-tuned to optimize model performance.

# Results
The results demonstrate that the DistilBERT model outperforms the count-based baseline in terms of classification accuracy. While the DistilBERT model offers higher accuracy, the count-based approach is computationally faster. The research also explores the impact of hyperparameters on model effectiveness.

# Conclusion
This project highlights the effectiveness of pre-trained transformer models, like DistilBERT, in movie genre classification based on plot summaries. The findings indicate that a lower learning rate, larger batch size, and more training epochs improve model performance. Future work could extend this research to classify other types of genres, such as music or literature.

This work provides insights into the application of NLP techniques to movie genre classification and demonstrates the potential of pre-trained transformer models in this domain.
