# NLP sarcasm classifier
- This model marks the beginning of my experience with NLP and serves the purpose of familiarizing myself with the tools, terminology, and optimization methods.
- In this project, I've built and trained a neural network using natural language processing techniques to classify sarcastic news headlines.
- This is a binary classification problem that require knowldge of NLP, tokenization, and sequencing the sentences to make it understandable for the model. 
- The dataset ~28k headlines, is publicly available on kaggle: https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection
- I've split the data in train, cross-validation, and test test with propotions of 86%, 7%, and 7% respectively.
- After training, the accuracy scores are 90.31% , 85.17%, and 85.87% respectively.
- To ensure the model's generalizability, I've plotted the ROC-curve and calculated the AUC-score to be 0.936 and they both supported the model's roboust performance.
- Digging deeper, I looped over the threshold values used for the ROC-curve to see which one optimizes the F-1 score and fount that a threshold of 37.47% pushed the F-1 score to 0.85 with recall of 0.89, precision of 0.82, and accuracy of 85.87% on the test set which ensures the model's rigidity on new unseen data.
