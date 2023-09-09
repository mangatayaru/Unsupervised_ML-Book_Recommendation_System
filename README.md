# Unsupervised_ML-Book_Recommendation_System
During the last few decades, with the rise of Youtube, Amazon, Netflix, and many other such web services, recommender systems have taken more and more place in our lives. From e-commerce (suggest to buyers articles that could interest them) to online advertisement (suggest to users the right contents, matching their preferences), recommender systems are today unavoidable in our daily online journeys. In a very general way, recommender systems are algorithms aimed at suggesting relevant items to users (items being movies to watch, text to read, products to buy, or anything else depending on industries). Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. The main objective is to create a book recommendation system for users.

The Book-Crossing dataset comprises 3 files.

The users file conatins the User IDs which are anonymized and map to integers. Demographic data is provided (Location, Age). There are more null values in the age column.

Books are identified by their respective ISBN. Moreover, some content-based information  is provided in the book dataset  (Book-Title, Book-Author, Year-Of-Publication, Publisher), URLs linking to cover images are also given, appearing in three different flavours (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

The ratings file contains the book rating information.

The Pandas library is used for data manipulation, aggregation.
Matplotlib and Seaborn is used for visualization and behavior with respect to the target variable.
