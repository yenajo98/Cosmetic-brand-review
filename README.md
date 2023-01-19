# Cosmetic-brand-review


### Why I planned for this analysis?
I wanted to review the models and theories I learned in my programming classes. 
From EDA, visualizing data to sentiment analysis using NLP. 

### Thoughts & Results
EDA was thorough and gave me insights on the data, answering all three questions I had: 
1. Which brand has the highest average review rating?
2. Which month has the most popular review?
3. Is there a relationship between "buyer" and "review_rating"? i.e. Do buyers tend to give high review rating?

### Limitation
I tried to go a step further by applying feature_extraction method(TfidfVectorizer) which I learned from class, but it didn't give me the best result. 
However, the method I used for sentiment analysis could have produced a better result. The clustering was very ambiguous for both bad and good reviews.

### Future recommendations
* * I was setting the criteria for bad and good reviews, which could have also produced inaccurate result. So next time, I will find out the method to an objective way of classifying good and bad reviews
* * Finding optimal K-means could have worked out better. This might be because of a small dataset. Therefore, I should find a bigger dataset for sentiment analysis next time.  


### Data sources
The data sources are from Kaggle https://www.kaggle.com/datasets/jithinanievarghese/cosmetics-and-beauty-products-reviews-top-brands



