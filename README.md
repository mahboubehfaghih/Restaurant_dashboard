# Where should you eat in Europe? Analysis & Visualization
- Type of Challenge: `Consolidation`
- Duration: `2 weeks`
- Deadline: `30/06/2022 4:30 PM`
- Presentations: `01/07/2022 1:30 PM`
- Teams: Solo or Pairs

## The Mission

You are a data analysis consultant at an European travel agency. Your mission is to help the company find business insights from their data that will help them grow their business. 

To do so, you will create a dashboard! What is important to include in the dashboard? Ideally, this dashboard would help travel agents make recommendation to travellers on the best food destination for their trips across Europe.

As a starting point, they provide you with data they scrapped from Trip Advisor, a popular travel website. 

Dataset: [TripAdvisor Restaurants Info for 31 Euro-Cities](https://www.kaggle.com/datasets/damienbeneschi/krakow-ta-restaurans-data-raw)

### Must-have features

- Create a dashboard that showcases business insights for the client.

## Dataset and Attribute information:

This dataset contains information scrapped from the TripAdvisor website about restaurants in 31 European cities. The cities listed are from different European countries: Amsterdam (NL), Athens (GR), Barcelona (ES), Berlin (DE), Bratislava (SK), Bruxelles (BE), Budapest (HU), Copenhagen (DK), Dublin (IE), Edinburgh (UK), Geneva (CH), Helsinki (FI), Hamburg (DE), Krakow (PL), Lisbon (PT), Ljubljana (SI), London (UK), Luxembourg (LU), Madrid (ES), Lyon (FR), Milan (IT), Munich (DE), Oporto (PT), Oslo (NO), Paris (FR), Prague (CZ), Rome (IT), Stockholm (SE), Vienna (AT), Warsaw (PL), and Zurich (CH).

There are 125527 restaurants listed in the dataset. The attributes with respect to each restaurant are:

1.Name: Name of the restaurant.

2.City: City location of the restaurant.

3.Cuisine Style: Cuisine style(s) of the restaurant, as a Python list.

4.Ranking: Rank of the restaurant among the total number of restaurants in the city, as a float object.

5.Rating: Rate of the restaurant on a scale of -1 to 5, as a categorical type.

6.Price Range: Price range of the restaurant among 3 categories, as a categorical type.

7.Number of Reviews: Number of reviews that customers have given to the restaurant, as a float object.

8.Reviews: Reviews given by the customers to the restaurant, as a list of list object where the first list contains the 2 reviews, and the second, the dates when these reviews were written.

9.URL_TA: A part of the URL of the detailed restaurant page that comes after 'www.tripadvisor.com' as a string object.

10.ID_TA: Identification of the restaurant in the TA database.

There are missing information about the restaurants in the dataset, as NAN.

## Visualization:

Analysis of various features like price range, ratings and reviews to find out the best restaurants in different cities in Europe, which offer good food for its customers.

## Analysis:

We have over 125K restaurants in 31 European cities... plenty of places to try!

The most restaurants are located in London followed by Paris. 

There are 127 Cuisines in the dataset.
- European: European, Dutch, French, Central European, Italian, Irish, German, Belgian, British, Spanish, Swiss, Scandinavian

- Middle Eastern: Mediterranean, Lebanese, Arabic, Turkish, Moroccan, Tunisian, Persian

- Asian: Asian, Indonesian, Japanese, Chinese, Indian, Tibetan, Nepali, Thai

- Others: International, New Zealand, American, Argentinean, South American, Latin

- Healthy Options: Vegetarian Friendly, Vegan Options, Gluten Free Options, Healthy

- Bars: Bar, Pub, Wine Bar

- Specific: Diner, Cafe, Fast Food, Pizza, Seafood, Sushi, Soups, Delicatessen, Contemporary, Halal, Grill, Barbecue, Steakhouse.

Vegetarian Friendly is the top cuisine style by number of reviews and ratings in all the cities.

The WordCloud was an overall view of the reviews scraped from TripAdvisor.com.

histogram show words in common, which in general can be related to the matter people are talking about (like food , service , good).

In accordance with the histogram, the WordCloud is dominated by positive words.


## Conclusion

What surprised me the most about this analysis is the focus customers put on cuisine styles like the Vegan, Vegetarian or Gluten Free. Seeing them so talked about around Europe gave me a different perception of them.

The words used to describe the experiences (as well as the ratings) are in general positive and, I think because of the kind of data we avail of, the reviews are mostly about the kind of experience (service, location, price) and not about food itself.

I think with this analysis, there are many answers to the question "Where should you eat in Europe?". There are many restaurants in these European cities and a variety of cuisines and price ranges to choose from. So, you have a lot of options depending on where you are and what you feel like eating. More visuals can be done with this dataset but I think for now I've covered the ones that seem the most inetersting and useful.

# Installation

- Power BI

# Contributor

- #### [Mahboubeh Faghih Mohammadi](https://github.com/mahboubehfaghih)
    - https://www.linkedin.com/in/mahboubeh-faghih-mohammadi/
