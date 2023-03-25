# Email Classification using NLP with TensorFlow
Spam or Not 📧 

Purpose of this notebook to classify email in two categories spam or not using NLP

About Dataset:
- We're using public dataset which includes two columns text (email) and spam (label)
- if text label is 1 it's spam otherwise 0.
- [Dataset Link](https://www.kaggle.com/bagavathypriya/email-spam-dataset)

NLP Flow
```
text -> turn it into number -> build a model -> train a model -> use patterns for making prediction
```

### Approach Towords Project
- Get data and Visualize
- Preprocess Data
- Split data into train and test
- Converting "text" into numbers
- Running Series of Experiments
  1. Naive Bayes
  
  2. Simple Dense Layer
  
  3. LSTM (Long Short Term Memory Networks)
  
  4. Bidirectional RNN
  
  5. Conv1D
  
- Comparing results of all models

