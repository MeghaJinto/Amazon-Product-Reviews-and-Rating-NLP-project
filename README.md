Amazon reviews play a crucial role in the decision-making process for consumers, especially as online shopping grows. Customers rely on reviews to assess product quality, and research shows that over 90% of consumers check reviews before purchasing. Good reviews increase trust and purchasing confidence, especially for unfamiliar products or brands. Positive reviews drive sales, while negative ones can deter purchases and impact brand reputation. This effect is particularly pronounced for high-end items and functional goods, where potential buyers want assurances of quality and reliability.
The main objective of the project is typically to analyze and derive meaningful insights from vast amounts of customer feedback. These project use NLP to process, categorize, and interpret the sentiments and themes present in product reviews, providing valuable information for both Amazon and sellers. 
Here are some core goals commonly associated with such projects:
1.	Sentiment Analysis: NLP technique textblob is used to classify reviews as good, bad, or neutral, giving a quick snapshot of customer sentiment for products. 
2.	Sentiment Score: NLP technique SentimentIntensityAnalyser is used to find the intensity or score of each review. Sentiment scores help Amazon prioritize certain reviews and give sellers feedback on how customers feel about their products.
The dataset used in this project contains information about diamonds, including:
•	Product-Id: The unique Id of the Product.
•	Product name: The name of the Product.
•	Category: The category (Computers&Accessories, Electronics, Electronicsecor, MusicalInstruments,OfficeProducts, Home&Kitchen,HomeImprovement, Toys&Games, Cars&Motorbike, Health&PersonalCare).in which the Product belongs to.
•	Discounted price: The discounted amount of each product.
•	Actual Price: The actual price of each product.
•	Discounted percentage: The percentage of discount given to each product.
•	Rating: Rating given to each product.
•	User-Id: The unique id of user who reviewed the product.
•	Review title: Reviews of each product given by user.
Methodology
1.	Data Preprocessing:
o	Handle missing values and outliers.
o	Cleaning the data using Regex.
o	Standardize numerical features.
o	Preprocessing the data using nlp techniques such as fasttext, lemmatization , stopwords and punctuation,
2.	Exploratory Data Analysis (EDA):
o	Visualize relationships between category, actual price, discounted price, discount percentage and reviews.
3.	Processing and finding the score :
o	Using nlp technique textblob find and categorize the reviews as good, bad or neutral.
o	Using nlp technique SentimentIntensityAnalyser to find the score of each review.
The project provides significant value to consumers, sellers and Amazon by creating a more transparent and informative review system, allowing for improved purchasing decisions and product quality assessments.
