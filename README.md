# **Project Title : Amazon consumer Behaviour**

##**Problem Statement:**

Given the Amazon Consumer Behaviour Dataset, our goal is to analyze and understand the purchasing behavior and preferences of Amazon customers. By exploring various demographic and behavioral attributes, we aim to uncover insights that can help Amazon enhance its services, personalize recommendations, and improve the overall shopping experience for its customers.

**Dataset Names:**

1. **amazon_consumer_behaviour.csv**
2. **age**: Age of the respondents
3. **gender**: Gender of the respondents
4. **purchase_frequency**: Frequency of purchases made on Amazon
5. **purchase_categories**: Product categories typically purchased on Amazon
6. **personalized_recommendation_frequency**: Frequency of purchases based on personalized recommendations
7. **browsing_frequency**: Frequency of browsing Amazon's website or app
8. **product_search_method**: Method used for searching products on Amazon
9. **search_result_exploration**: Preference for exploring search results
10. **customer_reviews_importance**: Importance of customer reviews in decision-making
11. **add_to_cart_browsing**: Usage of "Add to Cart" feature while browsing
12. **cart_completion_frequency**: Frequency of completing purchases after adding to cart
13. **cart_abandonment_factors**: Factors influencing cart abandonment decisions
14. **save_for_later_frequency**: Frequency of using the "Save for Later" feature
15. **review_left**: Participation in leaving product reviews on Amazon
16. **review_reliability**: Reliability of product reviews in decision-making
17. **review_helpfulness**: Perceived helpfulness of customer reviews
18. **personalized_recommendation_frequency**: Frequency of receiving personalized recommendations
19. **recommendation_helpfulness**: Perceived helpfulness of personalized recommendations
20. **rating_accuracy**: Rating of relevance and accuracy of recommendations
21. **shopping_satisfaction**: Satisfaction level with the overall shopping experience
22. **service_appreciation**: Aspects of Amazon's services appreciated the most
23. **improvement_areas**: Areas where Amazon can improve according to respondents

**Summary:**

The Amazon Consumer Behaviour Dataset provided valuable insights into the purchasing behavior and preferences of Amazon customers. The dataset contained various demographic and behavioral attributes such as age, gender, purchase frequency, product categories, personalized recommendation frequency, and more. Our objective was to analyze this dataset to understand customer behavior better and identify areas for improvement in Amazon's services.

We began by performing one-hot encoding to preprocess categorical variables and prepare the data for modeling. Subsequently, we applied logistic regression, random forest, SVM classifier, and KNeighbors classifier to predict customer behavior. However, the initial results showed poor performance due to the unbalanced nature of the dataset.

To address this imbalance and improve model performance, we applied the Synthetic Minority Over-sampling Technique (SMOTE) to oversample the minority classes. We then performed hyperparameter tuning on the Random Forest classifier, which resulted in significant improvements in precision, recall, and F1-score for all classes.

**Conclusions:**

1. **Data Understanding**: The analysis of the Amazon Consumer Behaviour Dataset provided valuable insights into various aspects of customer behavior on the platform.

2. **Model Performance**: The initial models showed poor performance due to the unbalanced dataset. However, by applying SMOTE to address the class imbalance and performing hyperparameter tuning on the Random Forest classifier, we achieved significant improvements in model performance.

3. **Recommendations**: Based on the improved model performance, we recommend that Amazon leverage these insights to enhance its services, personalize recommendations, and improve the overall shopping experience for its customers. Areas such as personalized recommendations, customer reviews, and browsing experience could be prioritized for further enhancement.

4. **Future Work**: Future work could involve exploring additional modeling techniques, such as ensemble methods or deep learning algorithms, to further improve predictive performance. Additionally, collecting more granular data and conducting deeper analyses could provide additional insights into customer behavior and preferences.
