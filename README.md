<p align="center">
  <img src="https://github.com/Tahascommit/Clustering-and-analyzing-sentiments-for-restaurants-on-Zomato-ML-NLP/blob/a66fefdd4cf739196326e80da0de0a664fd0e860/gifs/Zomato%20Restaurant%20clustering%20and%20sentiment%20analysis.png" width="703" height="340">
</p >


# ML-NLP-Clustering And Analyzing Sentiments For Restaurants On Zomato
#### Objectives:

1.  **Cluster Zomato Restaurants**: Group restaurants into distinct clusters.
2.  **Sentiment Analysis of Reviews**: Analyze customer reviews to determine positive or negative sentiments, providing insights into customer satisfaction and preferences.

#### Business Context:

*   **Background**: Zomato, an Indian restaurant aggregator and food delivery service, has seen an evolution in the restaurant business in India. The growing number of restaurants and their diversity calls for an insightful analysis of this sector.
*   **Relevance**: This project is crucial for understanding customer preferences, improving service quality, and enhancing the dining experience in India's dynamic food industry.

#### Data Utilization:

*   **Data Sources**: Restaurant data from Zomato.
*   **Sentiment Analysis**: Customer reviews will be analyzed to extract sentiment polarity (positive or negative).

#### Methodology:

1.  **Data Preprocessing**: Cleaning and structuring data for analysis.
2.  **Clustering Technique**: Utilizing unsupervised machine learning algorithms (like K-means, hierarchical clustering, DBSCAN) to group restaurants.
3.  **Sentiment Analysis**: Employing NLP techniques to analyze and categorize the sentiments of user reviews.

#### Outcomes:

*   **Visualizations**: Graphical representations of clusters and sentiment analysis results for easier interpretation and decision-making.
*   **Insights for Customers**: Assisting customers in finding the best-suited restaurants based on their preferences.
*   **Business Strategy for Zomato**: Identification of areas for improvement, popular cuisines, and customer preferences to strategize business growth and customer satisfaction.

#### Impact:

*   **For Customers**: Enhanced decision-making in choosing restaurants aligning with their preferences.
*   **For Zomato**: Strategic insights into customer preferences, leading to better service offerings and targeted marketing.

#### Applications:

*   **Customer Segmentation**: Identifying different customer segments for targeted marketing.
*   **Market Analysis**: Understanding popular trends in cuisines and dining experiences.
*   **Operational Improvement**: Identifying gaps in service and areas for improvement.
*   **Critic Analysis**: Using reviewer metadata to identify influential critics in the industry.

#### Models used for Restaurant Clustering:

1. K-Means clustering  (Selected)
2. Hierarchical clustering
3. DBSCAN

#### Models used for Sentiment Analysis:

*   Logistic Regression (Selected after hyperparameter tuning and cross-validation)
    
    *   Accuracy: 87.8% - This was the highest among all models.
    *   Precision: Exhibited a good balance, slightly higher for class 1 (positive sentiment).
    *   Recall: Was better at identifying class 1 (positive sentiment), with a notable difference compared to class 0 (negative sentiment).
    *   F1-Score: Was high for both classes, particularly for class 1, indicating a strong overall performance.
*   Random Forest
    
    *   Accuracy: 85.94% - Slightly lower than Logistic Regression.
    *   Precision and Recall: Were comparatively lower than Logistic Regression, especially recall for class 0 (negative sentiment) which was significantly lower.
    *   F1-Score: Fair for both classes but lower than Logistic Regression, especially for class 0.
*   XGBoost
    
    *   Accuracy: 86.39% - Close to Logistic Regression, but slightly lower.
    *   Precision and Recall: Were balanced, with a marginal preference for class 1. Recall for class 0 was better than Random Forest but not as good as Logistic Regression.
    *   F1-Score: High for both classes, indicating effective performance, particularly for class 1.
*   Gradient Boosting
    
    *   Accuracy: 84.08% - The lowest among the models.
    *   Precision and Recall: Precision was relatively balanced, but recall was notably lower for class 0, affecting its overall performance.
    *   F1-Score: Lower for class 0, indicating challenges in identifying negative sentiments as effectively as other models.

#### Restaurant Clustering (K-Means) Snap:

<img src="https://github.com/Tahascommit/Clustering-and-analyzing-sentiments-for-restaurants-on-Zomato-ML-NLP/blob/e870f527d3a1a9bda909eae286c06b7f841ff812/gifs/kmeans_3d.gif" width="670" height="280">

#### Predicting Restaurant Cluster (K-Means) for new data with trained model:

<img src="https://github.com/Tahascommit/Clustering-and-analyzing-sentiments-for-restaurants-on-Zomato-ML-NLP/blob/f5c6aa0ce711ed01ff518d9933d070ea4665755a/gifs/k_means_pred.png" width="1000" height="350">

#### Predicting Sentiment for new data with trained model:

<img src="https://github.com/Tahascommit/Clustering-and-analyzing-sentiments-for-restaurants-on-Zomato-ML-NLP/blob/1657550202174e9f15465be2fbc12e1448f2563c/gifs/Sentiment_pred.png" width="1000" height="350">


