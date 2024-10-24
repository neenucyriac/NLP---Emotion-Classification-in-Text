# NLP---Emotion-Classification-in-Text

1. Loading and Preprocessing (3 marks)
. Explain the preprocessing techniques used and their impact on model performance.
#Impact on Model Performance:

#Text Cleaning: 
'''Helps in reducing noise in the data, which allows the model to focus on meaningful words.'''
#Tokenization: 
'''Converts text into a structured format for further analysis.'''
#Stopword Removal: 
'''Reduces dimensionality and improves model performance by eliminating non-informative words.'''


#2. Feature Extraction (2 marks):
'''Implement feature extraction using CountVectorizer or TfidfVectorizer. Describe how the chosen method transforms the text data into numerical 
features.'''

'''
TF-IDF: Stands for Term Frequency-Inverse Document Frequency. It increases the weight of words that are frequent in a document
but not across all documents, thus highlighting unique terms that may be important for classification.'''

#4. Model Comparison (2 marks)
'''Evaluate the model using appropriate metrics (e.g., accuracy, F1-score).
Provide a brief explanation of the chosen model and its suitability for emotion classification.'''

'''
Suitability of Models:

Naive Bayes: Works well with text data, especially when the features are conditionally independent. 
It's computationally efficient and performs well for multi-class classification problems.


SVM: Effective in high-dimensional spaces and particularly useful for text classification due to its ability to find hyperplanes
that best separate classes.
