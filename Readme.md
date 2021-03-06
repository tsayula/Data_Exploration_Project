![Pizza vs. Bike Shops in Austin](https://upload.wikimedia.org/wikipedia/commons/a/a5/Austin_Evening.jpg)

# Austin Business Comparison Analysis
# Comparing 2 Markets

**Collaborators**: [Mark Rubin, Lera Tsayukova]

## Overview


This project aims to analyzes the local business needs of the great city of Austin, Texas, whos local slogan "Keep Austin Weird" was inspired by
the cities small business alliance [Austin Indepedent Business Alliance](https://ibuyaustin.com) to promote small businesses!

While Austin is a booming metropolis City, we aim to analyze whether a pizza shop or a taco shop would be more lucrative!

## Method

**By analyzing data directly from Yelp's API, we were able to collect a data set of 141 Taco shops and 189 Pizza shops.
-Then we sourced a total of nearly 1,000 reviews combined for both taco and pizza shops.
-We evaluated this data by using various combinations of the following metrics: 
        *total number of businesses for each category
        *average ratings
        *total number of reviews
        *price point
        

## Data 


 
**Step 1: Contrast the number of pizza and taco restaurants by their respective price points:
        ![bargraph of all restaurants by price point](https://github.com/tsayula/Bikes_Repo/blob/main/visualizations/pizza_tacos_price.png?raw=true)
       
*There is a plethora of higher priced pizza shops, compared to taco restaurants.
________________________________________________
**Step 2: Analyze the ratings of taco shops and pizza shops by the total number of reviews:
        ![horizontal graph of total reviews by rating]<img src="https://github.com/tsayula/Bikes_Repo/blob/main/visualizations/Biz_Rev_Counts_By_Rating.png?raw=true" width="500" height="400">        
       
*Reviewees of taco shops seem to leave feeback when the experience is average (3 star), whereas patrons of pizza restaurants are more inclined to review
their experience the better it is (4-5 star).
________________________________________________
**Step 3: Comparing Austin's taco shops to pizza shops by average rating:   
![bargraph comparing total number of each category](https://github.com/tsayula/Bikes_Repo/blob/main/visualizations/Avg_Rtng_by_Category.png?raw=true)

*The reviews on average are higher for taco restaurants than pizza restaurants.**


**Step 4: Evaluate the total number of observations for each star rating (1-5) by Category (Pizza, Tacos):
        ![histogram of avg ratings by frequency](https://github.com/tsayula/Bikes_Repo/blob/main/visualizations/histogram_ratings.png?raw=true)
        ![barchart of avg rating by frequency](https://github.com/tsayula/Bikes_Repo/blob/main/visualizations/Num_Of_Biz_By_Rating.png?raw=true) 
    
*Taco shops are either rated very well or very poorly, while pizza restaurants are more consistent with reviews to ratings**

________________________________________________
________________________________________________


<img src="http://www.austinbike.com/images/sliders/one.jpg" width="300" height="150">

## Analysis Summed

-The reviews on average are higher for taco restaurants than pizza restaurants.
-There is a plethora of higher priced pizza shops, compared to taco restaurants.
-Reviewees of taco shops seem to leave feeback when the experience is average (3 star), whereas patrons of pizza restaurants are more inclined to review
their experience the better it is (4-5 star).
-Taco shops are either rated very well or very poorly, while pizza restaurants are more consistent with reviews to ratings.

<img src="https://3vi9mx40b3afabx1fqvvhk9e-wpengine.netdna-ssl.com/wp-content/uploads/2020/07/40-North-nor-cal-horizontal.jpg" width="400" height="200">


## Conclusions

This analysis leads to several conclusions:

- **The results of our analysis found that in Austin,Texas it would be better to invest in a pizza shop. 
- **We made this conclusion because the mean value of the Taco business ratings is significantly higher than the mean value of the Pizza business ratings.
- **As an additional support to our conclusion, our results show that Taco businesses are distributed much less evenly among the ratings scale, and are more centralized between the four and five star ratings. This brought us to the conclusion that there were less highly-rated businesess to compete against in the Pizza market. 
- **Pizza patrons are more likely to review their experience to when it is positive, in comparison to taco connouisseurs who rate establishments mostly when the experience is just average (3 stars)
- **Our results also indicate that people are more willing to pay higher prices for Pizza. The frequency of reviews for Pizza restaurants with a 5 rating was also significantly lower which led us to conclude that there is higher potential for a high end pizza parlor in Austin.
- also a stronger market opportunity for opening a higher end pizza parlor .
- 
### Next Steps

More involved analyses could yield additional insights.
- **Implement Geopandas modeling, use Census data 
- **Acquire financial data in targeted zip codes to help make better predictions
- **Broaden our query to determine the best Retail store or Restaurant Type to open. 


## For More Information

See the full analysis in the [Jupyter Notebook](./Final_Notebook.ipynb) or review this [InSerT PresentTaton](./HEYinsertMEhere.pdf).

For additional info, contact Mark Rubin or Lera Tsayukova.
![Image of Keep Austin Wierd](https://res.cloudinary.com/culturemap-com/image/upload/ar_4:3,c_fill,g_faces:center,w_980/v1521047613/photos/28712_original.jpg)

## Repository Structure

```
├── images
├── data
├── visualizations
├── Austin_business_analysis.ipynb
├── README.md
└── Final_Notebook.ipynb
├── Austin_Presentation.pdf
```
