# Sentiment Analysis of Quick Commerce Platforms  

## Project Overview  

This project focuses on analyzing customer reviews for three major quick commerce platforms: **BlinkIt, Zepto, and JioMart**. By leveraging **Natural Language Processing (NLP)** techniques, the goal is to assess customer sentiment, compare platform performance, and identify key pain points that impact user experience.  

The insights derived from this analysis can help these platforms enhance service quality, improve customer satisfaction, and gain a competitive advantage in the quick commerce industry.  

## Dataset  

The dataset contains customer reviews along with rating points for BlinkIt, Zepto, and JioMart. The presence of all three platforms in a single dataset allows for a comprehensive comparative analysis of their service quality and user satisfaction.  

### Features:  
- **Review Text**: Customer feedback on their experience.  
- **Platform Name**: Identifies the platform (BlinkIt, Zepto, JioMart).  
- **Rating**: Numerical representation of customer satisfaction.   

## Methodology  

1. **Data Preprocessing**  
   - Tokenization and stopword removal  
   - Lemmatization for text normalization  
   - Vectorization using **TF-IDF** or **Word Embeddings**  

2. **Sentiment Classification**  
   - Built a classification model using **deep learning** with TensorFlow/Keras.   

3. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, and F1-score were used to assess model performance.  
   - A classification report was generated to understand the effectiveness of the sentiment classification.  

## Results  

The classification model achieved near **100% accuracy** on the test dataset, indicating excellent performance in distinguishing between different sentiment categories.  

### Key Findings:  
- High accuracy in classifying user sentiments across all platforms.  
- Identified major pain points affecting customer satisfaction.  
- Found critical areas for service improvement in quick commerce platforms.  

## Challenges and Future Improvements  

- **Addressing Overfitting**: Since the model achieved very high accuracy, further validation on unseen data is needed to confirm generalization.  
- **Model Optimization**: Implementing regularization techniques or fine-tuning hyperparameters to improve robustness.  
- **Dataset Expansion**: Adding more diverse reviews to capture broader user perspectives.  
- **Aspect-Based Sentiment Analysis**: Extracting insights on specific service aspects (e.g., delivery speed, product quality, customer support).  

## Conclusion  

This project provides a **data-driven approach to understanding customer sentiment** in quick commerce services. By identifying user concerns, the findings can help platforms optimize their operations, enhance customer satisfaction, and build a **sustainable competitive edge**.  

## Technologies Used  

- **Python**  
- **Pandas, NumPy** – Data processing  
- **NLTK** – Text preprocessing  
- **TensorFlow/Keras** – Deep learning models  
- **Scikit-learn** – Model evaluation  
- **Matplotlib, Seaborn** – Data visualization  
