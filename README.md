# CNN Website posts: A Sentiment Analysis 

Our project utilizes Facebook data from 'data.world' to conduct sentiment and demographic analyses, enriched with contributions from Cable Network News (CNN) channel's news outlet. Through machine learning techniques, we aim to provide an interactive platform for tailored insights. Our user-friendly interface simplifies sentiment analysis, antagonist identification, and engagement metrics comprehension. By deciphering demographic characteristics' impact on sentiment, we offer nuanced insights for News curators, Social media analysts and marketers. This initiative democratizes data analysis, offering instantaneous insights into public sentiment and informing strategic business decisions.

## Business Objective

To use records of CNN news posted from 2012- 2017, to provide insights into user behavior and sentiment dynamics, thereby enabling informed decision-making to enhance marketing strategies and campaign effectiveness.

### Tools used

- Microsoft Excel
  
- Tableau

- Python

- Machine Learning techniques

### Methodology

**Step 1:** Data Cleaning to inspect column/data types and treat missing values.
**Step 2:** Data Preprocessing:
- Text Cleaning: We removed unnecessary characters, URLs, and special symbols from the text to create a standardized dataset for analysis.
- Tokenization: The text was broken down into individual words or tokens, a crucial step for further text analysis.
- Stop words Removal: Common words that typically don’t contribute to sentiment, such as "the" and "and," were eliminated.
- Lemmatization/Stemming: Words were converted to their base or root form to simplify the analysis.

**Step 3:** Exploratory Data Analysis using Tableau dashboards to understand the features and sentiments hidden in the data

**Step 4:** Sentiment Analysis using Machine Learning models and their evaluation for future use

Artificial Intelligence (AI) models to analyze sentiment and demographic information from social media data, particularly focusing on advanced Natural Language Processing (NLP) techniques. The models chosen are known for their effectiveness in text analysis and
sentiment classification.

- Naive Bayes Classifier: Ideal for sentiment analysis due to its simplicity and efficiency in handling large datasets. It’s used to classify posts into different sentiment categories based on the probability of word occurrences.
- Support Vector Machines (SVM): SVM is employed for its ability to find the hyperplane that best separates different sentiment classes in high-dimensional space, making it suitable for nuanced sentiment classification tasks.
- Recurrent Neural Networks (RNN): RNNs, particularly those with LSTM (Long Short-Term Memory) units, are utilized for their strength in handling sequences, making them ideal for analyzing the context within posts over time for sentiment analysis.
- Convolutional Neural Networks (CNN): Leveraged for deep learning-based sentiment analysis, CNNs are adept at capturing spatial hierarchies in text data, making them useful for extracting features from social media posts for sentiment classification.
- Decision Trees: Decision Trees are used for their interpretability and ease of visualization, aiding in the classification of posts based on sentiment by creating a model that predicts the sentiment value based on several input features.
- K-means Clustering: This unsupervised learning algorithm is used for segmenting the data into clusters based on post similarities, which can help in identifying prevailing topics or themes within the social media data.
- K-nearest Neighbors (KNN): KNN is applied for its simplicity and effectiveness in classification and regression problems. In the context of our project, it is used for classifying posts into sentiment categories based on the similarity of their features to those of known examples.

By integrating these AI models, we aim to achieve a nuanced analysis of sentiments and demographic patterns within the dataset, thereby providing comprehensive insights into user behavior and preferences on social media platforms. This multi-model approach allows for the leveraging of each model's unique capabilities, ensuring robustness and accuracy in our findings.

### EDA 



