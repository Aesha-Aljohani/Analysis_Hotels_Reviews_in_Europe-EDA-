# Analysis_Hotels_Reviews_in_Europe(EDA)

# Introduction:
The data was scraped from [Booking](https://www.booking.com/). All data in the file is publicly available to everyone already. Please be noted that data is originally owned by [Booking](https://www.booking.com/).

# Describe Data:
This dataset contains 515,000 customer reviews and scoring of 1493 luxury hotels across Europe. Meanwhile, the geographical location of hotels are also provided for further analysis.
# Data Content:
The csv file contains 17 fields. The description of each field is as below:

- Hotel_Address: Address of hotel.
- Review_Date: Date when reviewer posted the corresponding review.
- Average_Score: Average Score of the hotel, calculated based on the latest comment in the last year.
- Hotel_Name: Name of Hotel
- Reviewer_Nationality: Nationality of Reviewer
- Negative_Review: Negative Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Negative'
- ReviewTotalNegativeWordCounts: Total number of words in the negative review.
- Positive_Review: Positive Review the reviewer gave to the hotel. If the reviewer does not give the negative review, then it should be: 'No Positive'
- ReviewTotalPositiveWordCounts: Total number of words in the positive review.
- Reviewer_Score: Score the reviewer has given to the hotel, based on his/her experience
- TotalNumberofReviewsReviewerHasGiven: Number of Reviews the reviewers has given in the past.
- TotalNumberof_Reviews: Total number of valid reviews the hotel has.
- Tags: Tags reviewer gave the hotel.
- dayssincereview: Duration between the review date and scrape date.
- AdditionalNumberof_Scoring: There are also some guests who just made a scoring on the service rather than a review. This number indicates how many valid scores without review in there.
- lat: Latitude of the hotel.
- lng: longtitude of the hotel.

In order to keep the text data clean, I removed unicode and punctuation in the text data and transform text into lower case. No other preprocessing was performed.

# Questions:
1.	the Average rating of all hotels?
2.	Distribution of reviews to highly rated hotels?
3.	Rating of the worst hotels?
4.	What are the services that get the most complaints?

# Tools:
## Libraries:
-	Pandas for data preprocessing & analysis.
-	Numpy for numerical data manipulation.
-	Matplotlib for data visualization.
- Seaborn for statistical data visualization.
## Technologies:
- Jupyter notebook.
- Python.


# References:
- Datasets from kaggle [here](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe).
