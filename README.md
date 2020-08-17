# Amazon-cell-phone-review-analysis

In this project, I have used the text reviews given by Amazon users for mobile phones for analysis. The dataset was obtained from: [https://www.kaggle.com/grikomsn/amazon-cell-phones-reviews](Kaggle)

This dataset consists of about 68K user reviews for over 720 phones/brands sold on Amazon. This data is used to arrive at valuable insights to make data driven decisions.

In this project, we use Topic Modeling and Sentiment analysis to identify the major concerns that mobile phone customers share in the form of reviews and ratings. 

## Approach

We proceed to do this through different unsupervised learning approaches like Latent Dirichlet Allocation & Non-Matrix Factorization. An added interest is to use predictive modeling techniques like logistic regression, Support Vector Machine, Random Forest and Naïve Bayes classifier to predict user ratings from their text reviews.

## Analysis

We perform topic modeling for 3 major players in the Smartphone segment: Apple, Samsung and Xiaomi. 

70% of the reviews were skewed to 4 and 5 rating. A bi-modal distribution of ratings was observed for all the brands. This leads us to sentiment analysis.

We use standardized thresholds to classify sentences as either positive or negative. This is imperative given the skew of the ratings. So, we take a higher threshold of 0.5 to classify 4,5 ratings for the rest 0 cut off. We use both TextBlob and Vader for this purpose.

Next, we proceed to do topic modeling, which is a technique used to extract meaningful information from vast amounts of data. We try to label different topics among all the cell phone reviews in order to provide business recommendations to sellers. LDA and NMF are the two techniques we have used to do topic modeling.
