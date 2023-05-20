# British Airways Customer Buying Behaviour

<img src="images/brit.jpg" alt="British Airways Logo" style="display: block; margin-left: auto; margin-right: auto"/>

The national airline of the United Kingdom is British Airways (BA). 
Numerous BA planes bring passengers all around the world on their daily 
arrivals and departures from the UK. The aim of this project is to predict customer buying holiday.

# About the dataset

### Source

The [dataset]() used was obtained from BA via Forage Virtual Experience platform.

### Features

- review_rating: Overall customer review rating of a customer.
- review_title: The title of the review comment or post on the website.
- username_loc_date : The username, their location and date of posting.
- verified: Info of the review being verified or not.
- review_text: The review comment of a customer.
- aircraft: Type of aircraft flown.
- traveller_type: Type of travel.
- seat_type: Classes of the flight (Economy, Premium Economy, Business, First)
- route: Flight source to destination.
- date_flown: Date of flight/trip.
- seat_comfort: Rating of seat comfort during flight.
- cabin_staff_service: Rating of flight crew service during flight.
- food_beverages: Rating of food and beverages served during flight.
- inflight_entertainment: Rating of inflight entertainment.
- ground_service
- wifi: Rating of wifi service/quality.
- value_for_money: Rating of value for money on a scale of 1 to 5.
- recommended: Info concerning whether or not the customer recommended the airline in review.

# Libraries used

For the project the following Python libraries for Data Science and Machine Learning were used:
| Package | Function |
|---------|----------|
| numpy | For scientific computation |
| pandas | For data manipulation |
| matplotlib | For visualization |
| seaborn | For visualization |
| folium | For map views |
| nltk | For text preprocessing |
| sklearn | For machine learning |
| gensim | For topic modeling |
| bs4 | For parsing html |
| requests | For web scraping |
| wordcloud | For creating wordclouds |
| spacy | For lemmatization |

# Dashboard

An interactive dashboard was developed using Google Data Studio (Looker) to track key metrics that management 
can use to monitor the business.

![ba_dashboard](images/BA_dashboard.png)

Here is a link to the live [interactive dashboard](https://lookerstudio.google.com/reporting/dab728b0-fcb6-4ea6-96e0-474b7b69a876)

# Summary of Key Findings

After a slideshow was created for presentation of findigs, as stakeholders would prefer to see summaries and not code and every little technical detail.
Here is the [presentation](https://github.com/Izu-33/Forage---BA/blob/main/BA%20CUSTOMER%20REVIEW%20ANALYSIS.pdf).

# Modeling (k-Means, LDA, Vader)

- k-Means: k-Means clustering was used to cluster related words in the customer review comments (texts) and uncover
hidden underlying topics in the discussions of the customers.

- Latent Dirichlet Allocation (LDA): LDA is a generative probabilistic model of a corpus. This was used for topic
modeling as well.

- Vader: Used to build a model for sentiment scoring.


Link to test the sentiment analyzer: [link](https://sentalyzer-app.onrender.com/gradio/)

