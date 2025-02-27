# 487-sarcasm-detection
## Overview  
I'm working on sarcasm detection using machine learning. The dataset comes from [Kaggle](https://www.kaggle.com/datasets/nikhiljohnk/tweets-with-sarcasm-and-irony/data) and [Kaggle](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection). I tested a few models and built a simple UI to check sarcasm, but the detection isn't great yet.  

## What I Did  
- Used **Logistic Regression**, **SVM**, and **TF-IDF** for sarcasm classification.  
- Built a **Gradio UI** where users can input text to see if it's sarcastic.  
- Preprocessed text (tokenization, stopwords removal, etc.).  

## What's Wrong?  
- The **Logistic Regression model isn't good at detecting sarcasm**. It often fails because sarcasm is complex and context-dependent.  
- Many sarcastic tweets get misclassified as non-sarcastic.  

## Next Steps  
- Try other **deep learning models**. 
- Improve feature extraction for better sarcasm detection.  
- Maybe add context-aware analysis.  
