# Sentiment Analysis on Amazon Product Reviews

## Overview

This project focuses on sentiment analysis of Amazon product reviews using various machine learning and deep learning techniques. By categorizing customer feedback into positive, negative, and neutral sentiments, the project aims to provide actionable insights for product recommendations and enhance customer satisfaction.

## Objectives

- **Analyze Amazon customer feedback** to categorize sentiments.
- **Compare machine learning models** for effective sentiment analysis.
- **Implement both traditional and deep learning models** to understand customer sentiments and improve product recommendations.

## Methodology

1. **Data Collection and Preparation**:
   - The dataset consists of 400,000 Amazon reviews with two columns: a label indicating positive (1) or negative (0) sentiment and the review text.
   - Data cleaning steps include tokenization, lowercasing, removing punctuation, special characters, numbers, stop words, and applying lemmatization.

2. **Feature Extraction**:
   - Techniques such as TF-IDF, CountVectorizer, and Word2Vec are used to represent text data.
   - TF-IDF was selected as the preferred method due to its ability to highlight important words in reviews.

3. **Model Building**:
   - Various classification algorithms were tested, including Decision Tree, Random Forest, Naive Bayes, AdaBoost, Gradient Boosting, and XGBoost.
   - Deep learning models like RNN and LSTM were also evaluated but were less effective due to dataset limitations.

4. **Model Evaluation**:
   - GridSearchCV was used for hyperparameter tuning.
   - The best-performing model was the AdaBoost Classifier with TF-IDF, achieving a train accuracy of 0.86 and a test accuracy of 0.84.

## Results

- The analysis provides a robust recommendation system based on the sentiment of customer reviews.
- Positive reviews lead to product recommendations, while negative reviews prompt solutions to enhance user experience.

## Challenges and Limitations

- Traditional methods may overlook semantic nuances in text.
- The dataset size and complexity limited the performance of deep learning models like RNN and LSTM.
- Lack of analysis on subtle sentiments such as sarcasm and cultural context.

## Future Work

- Refining deep learning models and integrating pre-trained models like BERT for better accuracy.
- Exploring sentiment analysis across multiple modalities (text, images, audio).
- Developing personalized recommendations based on sentiment analysis insights.

## References

1. R. M. R. G. Malhar Anjaria, "A novel sentiment analysis of social networks using supervised learning," Journal of Theoretical and Applied Information Technology, vol. 4, 2013.
2. S. Maurya and V. Pratap, "Sentiment analysis on amazon product reviews," in 2022 International Conference on Machine Learning, Big Data, Cloud and Parallel Computing (COM-IT-CON), vol. 1, 2022, pp. 236–240.

*(Refer to the full report for additional references and detailed analysis.)*

## Contact

For more information or collaboration, please contact:

**Namia Mohamed Ali**  
Email: [nami29221@gmail.com](mailto:nami29221@gmail.com)

