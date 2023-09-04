#Amazon-Product-Review-Classification

The goal of the course project is to implement machine learning models and concepts covered in this course for a real-world dataset. The project will utilize the Amazon product review dataset and focus on binary classification, multi-class classification, and clustering approaches to analyze and categorize product reviews. All code must be implemented in Python and all models must use the Scikit Learn toolkit - https://scikit- learn.org/stable/index.html. You are not allowed to use other toolkits, such as NLTK or transformer network architectures, for your project results.

Here are examples of some useful Scikit modules:
● https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVect orizer.html
● https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.Hashing Vectorizer.html#sklearn.feature_extraction.text.HashingVectorizer
● https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVe ctorizer.html#sklearn.feature_extraction.text.CountVectorizer

## Information about the Dataset

● overall: This is the product’s rating on a scale of (1-5)
● verified: A boolean variable denoting if the review has been verified by Amazon
● reviewTime: time of review
● reviewerID: The unique ID of the Amazon reviewer (some have left multiple reviews)
● asin: Product ID. One product will have many different reviews
● reviewerName: Encoding of the Amazon reviewer’s username
● reviewText: The Amazon review
● unixReviewTime: unix time of review
● vote: How many people voted this review as being helpful
● image: If there is an image, link to the image
● style: If there is style information (e.g., size of shirt, color of phone), it is embedded in a
dictionary here. Only available for some samples
● Category: The Amazon product category of the product.

## Libraries Used
1. Pandas
2. Sckiti-learn
3. Numpy
4. Matplotlib

## Models trained

I developed models for Binary classification, Multiclass classification, and Clustering techniques. Logistic Regression, was the best performing model with baseline scores of 0.72, 0.76, 0.79, and 0.71 for different binary classification tasks. It also performed bettter for Multiclass classification with baseline score of 0.47.