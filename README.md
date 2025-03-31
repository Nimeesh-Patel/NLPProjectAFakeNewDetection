# News Classification Project

## Course
**NLP (Semester 6)** - Pillai College of Engineering

## Project Overview
This project is part of the Natural Language Processing (NLP) course for Semester 6 students at Pillai College of Engineering. The project focuses on **News Classification**, where we apply various **Machine Learning (ML)**, **Deep Learning (DL)**, and **Language Models** to categorize news articles into predefined categories. This project involves exploring techniques like:
- Text preprocessing
- Feature extraction
- Model training
- Evaluating the models for their effectiveness in classifying news articles.

You can learn more about the college by visiting the official website of [Pillai College of Engineering](http://www.pce.ac.in/).

## Acknowledgements
We would like to express our sincere gratitude to the following individuals:

- Theory Faculty:
  - Dhiraj Amin
  - Sharvari Govilkar

- Lab Faculty:
  - Dhiraj Amin
  - Neha Ashok
  - Shubhangi Chavan

Their guidance and support have been invaluable throughout this project.

## Project Title
Fake New Detection

## Project Abstract
The rapid expansion of social media has intensified the spread of misinformation, hate speech, and societal division, eroding public trust in information integrity. Many users struggle to differentiate factual news from misinformation, contributing to moral confusion and political instability. Traditional fact-checking methods and cyber policing have proven insufficient against the accelerating pace of false information dissemination, highlighting the urgent need for AI-driven solutions.

This project presents a Fake News Detection system leveraging Natural Language Processing (NLP) and various machine learning models to classify news articles as real or fake. By employing NLP techniques such as tokenization, stopword removal, stemming, and Term Frequency-Inverse Document Frequency (TF-IDF) vectorization, the models effectively identify deceptive linguistic patterns. Logistic Regression, Random Forest, Naïve Bayes variants, Decision Trees, Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Stochastic Gradient Descent (SGD), and transformer-based architectures like BERT and RoBERTa are trained on this processed data to learn decision boundaries and enhance detection accuracy.

The model performances are evaluated using accuracy, precision, recall, and F1-score, demonstrating their effectiveness in combating digital falsehoods. This work underscores the potential of machine learning and NLP in mitigating misinformation while emphasizing the broader need for digital literacy and ethical awareness in the information age.

## Algorithms Used

- Machine Learning Algorithms
  - Gaussian NB  
  - Logistic Regression  
  - Random Forest  
  - Multinomial NB  
  - Decision Tree  
  - SVM  
  - SGD Classifier  
  - KNN  
  - Bernoulli NB  

- Deep Learning Algorithms
  - CNN  
  - LSTM  
  - CNN-BiLSTM  

- Language Models
  - BERT  
  - RoBERTa  


## Comparitive Analysis
The comparative analysis of different models highlights their effectiveness in detecting fake news. The following table summarizes the accuracy, precision, recall, and F1-score of the models tested:
| Model              | Accuracy  (%) | Precision (%) | Recall (%) | F1-Score (%) |
|--------------------|----------|---------------|------------|--------------|
| Gaussian NB        | 70      | 70            | 69         | 69           |
| Logistic Regression| 68      | 71            | 70         | 68           |
| Random Forest      | 67      | 67            | 67         | 67           |
| Multinomial NB     | 66      | 69            | 68         | 66           |
| Decision Tree      | 65      | 65            | 65         | 65           |
| SVM                | 61      | 61            | 61         | 61           |
| SGD Classifier     | 58      | 78            | 54         | 44           |
| KNN                | 58      | 58            | 58         | 58           |
| Bernoulli NB       | 56      | 78            | 52         | 40           |
| BERT             | 94.00       | —           | —          | 93.91       |
| RoBERTa          | 93.00       | —           | —          | 92.91       |


## Conclusion

This Fake News Detection project highlights the effectiveness of Machine Learning and Natural Language Processing (NLP) techniques in identifying misinformation. Through a comparative analysis, Logistic Regression combined with NLP preprocessing demonstrated strong performance in classifying news articles as real or fake. The evaluation metrics—accuracy, precision, recall, and F1-score—confirm the reliability of this approach for detecting deceptive content.  

While traditional models like Logistic Regression provide a lightweight and interpretable solution, advanced models such as transformer-based architectures (e.g., BERT and RoBERTa) offer superior accuracy in misinformation detection. This project underscores the importance of combining AI-driven solutions with digital literacy efforts to combat the growing threat of fake news and misinformation in the digital age.
