---
layout: single
title:  "The Internet and American Beer Heritage"
date:   2022-12-14 00:01:59 +0100
categories: 
  - jekyll update
  - Layout
  #- Uncategorized
permalink: "/american-beer-heritage"

theme: minimal-mistakes-jekyll
minimal_mistakes_skin: "contrast"
read_time: true

# table of contents
toc: true
toc_label: "Cheers"
toc_icon: "beer"
toc_sticky: true

teaser: /assets/images/beerUS2.png
excerpt: "How does the internet carry the heritage of American beer? "

# header image
header:
  teaser: /assets/images/beerUS.png
  overlay_image: /assets/images/beerUS2.png
  overlay_filter: 0.1 # same as adding an opacity of 0.5 to a black background
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  actions: 
    - label: "Click Me"
      url: "https://www.youtube.com/watch?v=IML3jU_yyGs"
      
# author
#author: Ralph
  #location : "EPFL, Lausanne"

author_profile: True
---
# Beer

A word that carries memories of aromas, foam, good times, and a tad bit of a bitter taste. Is there anything better than cracking a cold beer on a sweaty, thirsty hot day at the beach, or chugging on IPA while cheering for your favorite sports team? The answer is no! Or at least according to 40% of drinkers in America, which makes :beers: beer the most popular alcoholic beverage in the United States. It has been the case since the 90's at least according to [Gallup][gallup], except for 2005 when wine took over briefly. But don't let the stats fool you: America's love story with beer goes way back - even before Europeans settled on the continent! This means the golden beverage has witnessed centuries of American history, from early European settlements until the inception of the United States, to recent times including the Prohibiton and finally the Internet Age. The first thing that comes to mind is that beer probably went through some changes during these 400 years. But is that what actually makes beer special to America? Hold my beer. What if the perception of beer in the common American memory was the real treasure here? Every generation perceived beer in the light of its own era, depending on the technologies available at the time. The result is a diverse heritage consisting of books, maps, and more recently, blogs. So how does the Internet carry the heritage of American beer? Here is our attempt to answer by resuming the early history of American beer, then analysing blog datasets in search for traces of that history in today's younger minds. 

![image-center](/assets/images/beers.jpg "https://unsplash.com"){: .align-center}

# Beer and America

Today, American beer comes in all shapes and forms. You have the choice between American lager, American pale ale, American Irish pale ale (or simply IPA), cream ale, American stout, American brown ale, and the list goes on! Now that you've chosen your beer, would you like it in a glass bottle? Or a can? Or perhaps draught in a jug? The beer industry today is simply gigantic and it is hard to keep track. Every single shop in the world has a beer fridge, major sports events around the globe are sponsored by beer, we even say "cheers" to say "thanks" or "goodbye" now what is happening here! It's more than just beer, it's culture. Now follow us to know how it all came to be.

![image-center](/assets/images/timeline.png "American beer timeline"){: .align-center}

- As early as the 10<sup>th</sup> century, Native Americans knew about fermented beverages and were already brewing various kinds of traditional beers from **corn** [[1]][natives-beer]. It is hard to imagine for most Americans but following the arrival of the first Europeans, the Natives taught them their own way of making beers. <br/>
- Corn beer lasted until the early 17<sup>th</sup> century, when the first English and Dutch settlers entered the American continent [[2]][concise-history]. Settlers started brewing **ale** at home, and the first Taverns of the New World saw the light. The beer business was still small and local back then as ale made in Europe was considered of higher quality, and was too expensive. <br/>
- In the 19<sup>th</sup> century came the **lager** revolution. With the big waves of German immigrants coming to North East America and after the end of the Civil War, the US saw a huge increase of beer popularity. If you're still not convinced the Germans caused the industrialization of beer in the US, here are some stats: the 1880 Census showed that 80.5 percent of the brewers were of German descent and the beverage industry had the heaviest German concentration among male employees [[3]][german-stats]. The 19<sup>th</sup> century also saw the birth of some of America's biggest beer companies like Anheuser-Busch and Pabst, who still dominate to this day. <br/>
- Enter the **Prohibition**. From 1920 to 1933, a nationwide constitutional law prohibited the production, importation, transportation, and sale of alcoholic beverages including beers. In case you're wondering why America went crazy at the time, the KKK counted ~3M member by the mid 1920's [[4]][kkk]. In the aftermath of the Prohibition, counties were allowed local control of alcohol. That means that each county became free to chose whether they wanted to keep the alcohol ban, or drop it. Counties that dropped the ban are called "wet", in opposition to "dry" counties where alcohol is still completely prohibited. Today, the US count 83 dry counties, home to ~1.7 million Americans, or 0.5% of the U.S. population [[5]][prohibition]. <br/>
- It's been a long way since the Prohibition's dark days. **Nowadays**, the US count more than 7'000 breweries, which range in size from industry giants to craft breweries. In 2021, 81% of all beer was domestically produced in the U.S, 13% of which was produced by craft breweries [[6]][beer-today].

# Beer and the Internet

![image-center](/assets/images/general-stats.png "RB and BA American numbers"){: .align-center}

Do we know how the average American from 1800 felt about beer at the time? There aren't even records of how much beer was brewed per year before 1800! That is why we find it fascinating that anyone can give their opinion about any beer on the **Internet**, which will keep it forever (*forever ever?*). We extracted data from two of America's biggest beer rating websites, **BeerAdvocate** (BA) and **RateBeer** (RB), to analyse and process Amerian users' ratings and reviews of a wide range of American beers. Let's start with a quick exploration of our datasets. 

![image-center](/assets/images/finish.png "Top 20 most rated Beers ratings"){: .align-center}

Here are the top 20 beers that users review. We notice that on the one hand, BeerAdvocate users tend to review beers that are the most preferred as the mean ratings are significantly high: above 4 out of 5. On the other hand, RateBeer users tend to review more mainstream beers, like Budweiser and Heineken with 1.5 and 2.1 average ratings respectively. <br>
![image-center](/assets/images/beer-cloud.png "What are people saying about beer?"){: .align-center}
![image-center](/assets/images/15-cloud.jpg "What words are used the most when reviewing?"){: .align-center}
We also generated word clouds from the reviews to check the words with highest occurences. As expected, we can see a stark difference between bad reviews (rating of 1/5) where beer is described as “watery”, “light”, “metallic” and "cheap", and excellent reviews (rating 5/5) where meliorative sensory terms are employed, like "aroma", "fruity", “fresh” and “hoppy”. 

# Heritage and Actuality

Let's recap. We went through America's beer history, from the arrival of ale to the emergence of lager with German immigrants, to the Prohibition then recent times where the market is booming. We also explored our American beer dataset, which contains Internet users' opinions about today's beer. But can we still find traces of the American beer heritage in modern beer rating websites?

## Ale vs Lager

The question of the century. Ale or lager? We've seen that ale precedes lager on the historical beer timeline. We also know that lager single-handedly caused the industrialisation of beer. But which is more popular on the websites? Ale or lager? We let the people decide.
<img src="/assets/images/avl-styles.png" alt="Unique beer styles in BA and RB" width="400" class="align-center"/> <br>
When it comes to beer styles counts, we can already see that ale comes in way more style variety than lagers on BeerAdvocate and RateBeer. This means that users tend to review different ale styles rather than lager styles. Lager seems to be considered more of a mainstream beer for beer connoisseurs, who would rather explore new tastes in the ale dimension. <br>
But what happened to the lager children, descendants of the mighty German immigrants? Do they still prefer their traditional lager beers over West European ale? In an attempt to answer, let's look at the "American German Belt". The Belt defines the area with densest German immigrant populations during the 18th century. It includes North Eastern states like Wisconsin, Minnesota, Ohio, Illinois, Michigan, Pennsylvania, and Iowa. 

![image-center](/assets/images/german-belt.png "History Vs Actuality (we made rigth map using Tableau)"){: .align-center}
The top map details the German immigration in the US circa 1872 [[3]][german-stats], while the bottom map visualizes the commitment of users across America with respect to produced beer made by their own state. To be precise, we're showing the number of local reviews within every state, divided by the state's population, multipied by 1000, to finally get the local reviews per capita (‰) for each state. (A local review defines a review on a beer that was produced in the user’s state). It is fascinating to see that German Belt users are still committed to their local beer scene even though lager became mainstream across the whole country! Beer is clearly still part of the culture there, and people are clearly involved when it comes to expressing their opinion about their local beers. <br>
But is the German Belt population still as interested in lager as back in the day? Let's check the reviews volume first and compare it to the rest of the states:
![image-center](/assets/images/avl-reviews.png "Ale vs Lager reviews count"){: .align-center}
We see no significant difference in review counts between the Belt and the rest, so the Belt does not tend to review lager more often. What about the ratings? Is the Belt prone to give better ratings to lager beer because of their cultural heritage? We aggregated the ratings across both websites to compute the average ratings of ales and lagers by the Belt across the years between 2002 and 2016.
![image-center](/assets/images/avl-ratings.png "Ale vs Lager ratings"){: .align-center}
 As the top graph shows, Belt users tend to rate ale better than lager, even though lager has catched up in recent years. Now looking at the difference between ratings from the German belt and the rest of the states (rest - belt), we see that the difference is negative. This means that Belt users tend to rate beers slightly better than the rest of the states, especially lagers between 2001 and 2011. But in recent years it seems like the difference is minimal (-0.025). So overall, it is hard to come to a definitive conclusion about German Belt users preferences. Beer styles evolve over time, just like users' preferences. We can not conclude that Belt users like lager better than other users, but we can say that beer is definitely still embedded in the local culture.

## Traces of Prohibition and more

On to a more recent topic. We know the influence of the Prohibition era, which happened 100 years ago, is still prevalent in the way Americans consume beer today, since some states still have dry counties where alcohol is prohibited. <br>
We hypothesize that dry states are more likely to give less favourable beer reviews in general, and particularly for beer that comes from wet states. <br>
In order to confirm or reject this hypothesis, we conduct two statistical tests: a linear regression that predicts the beer rating given a categorical attribute as input and an independent t-test on the sample means. <br>
The first categorical attribute that we analyze is whether the beer rating comes from a dry state. Since there are no completely dry states in the US as of 2022, we have considered states that contain dry counties as "dry states". The dry states are Arkansas, Florida, Georgia, Kansas, Kentucky, Mississippi, South Dakota, Tennessee, Texas [[8]][dry-counties]. <br>
In the linear regression, we find that there is a negative correlation between being in a dry state and writing a positive beer review. The t-statistic corresponding to this attribute is -8.45 (with a p-value of 3x10<sup>-17</sup>), which is statistically significant and confirms our initial hypothesis. For the independent t-test comparing the means, we obtain the same p-value.
![image-center](/assets/images/dry-positive.png ){: .align-center}
As we can see in the violin plots above, the ratings distributions are normal which means the t-test is valid. 

The second categorical attribute that we would like to take a closer look at is described as follows: we consider ratings written by a user coming from a dry state who is rating a beer that was brewed in a wet state. <br>
![image-center](/assets/images/dry-wet.png ){: .align-center}
A linear regression with this attribute yields a t-statistic of -10.70 (with a p-value of 1x10<sup>-26</sup>), which is even more statistically significant and confirms our initial hypothesis. For the independent t-test comparing the means, we obtain the same p-value.

|                                                     | t-statistic | p-value      |
|-----------------------------------------------------|-------------|--------------|
| Dry State Rating vs. Wet State Rating               | -8.45       | 3 x 10<sup>-17</sup>|
| Dry state user, Wet State Brewery vs. Everyone Else | -10.70      | 1 x 10<sup>-26</sup>|

In the same vein, we decided to explore other factors which may influence the rating of the beer depending on the user location. First, we hypothesize that people are more likely to give favourable reviews to beer that comes from the same state as the author of the rating. Second, we speculate that users are likely to give negative reviews to beers that come from their respective neighbouring states. For example, a user from California is expected to give a positive review to Californian beer and a negative review for beer from Nevada. As with the previous categorical attributes, we test these hypotheses with a linear regression and an independent t-test.
For the local beer reviews, we obtain a positive correlation between writing a review for local beer and giving a high overall rating. The t-statistic corresponding to this attribute is 51.775 (with a p-value of 0.00 -- a negligible numerical error), which is statistically significant and confirms our initial hypothesis. For the independent t-test comparing the means, we obtain the same p-value.
![image-center](/assets/images/local.png ){: .align-center}
For the neighbouring state beer reviews, we obtain a negative correlation with the final rating score. The t-statistic corresponding to this attribute is -11.444 (with a p-value of 2x10<sup>-30</sup>), which is statistically significant and confirms our initial hypothesis. We obtain the same p-value for the independent t-test.
![image-center](/assets/images/neighbor.png ){: .align-center}

|                             | t-statistic | p-value      |
|-----------------------------|-------------|--------------|
| Local vs. Outsider          | 51.775      | 0.00         |
| Neighbour vs. Non-neighbour | -11.444     | 2 x 10<sup>-30</sup>|

## Sentiment Analysis

<img src="/assets/images/beer-ad.png" alt="https://pinterest.com" width="400" class="align-center"/> <br>

On our journey from the past to the present, we have endeavored to share facts from many different perspectives about beer. So let's examine the sentiment analysis scores as an additional component of our data story. <br>
This is the first question we need to ask. Why is sentiment analysis crucial to learn what
users think about beers? Because the only recollection we have of the past beer market is old maps and cool beer ads! <br>
Technology advancements and the widespread use of websites like Beer Advocate and Rate
Beer have greatly facilitated people's previous beer experiences. Can we, therefore, observe
how negative the review content is if a beer has a low rating or how positive the review
content is if a beer has a high rating when analyzing the positive or negative feelings of
people's remarks regarding any beer? <br>
In the subsequent sentiment analysis, we used the twitter-XLM-roBERTa-base for
Sentiment Analysis model developed by [cardiffnlp][nlp].
This is a multilingual NLP model that has been optimized for sentiment
analysis using training data from 198M tweets.

![image-center](/assets/images/sentiment_scores.png ){: .align-center}

Looking at the figures above, we can see that for reviews with a rating of less than 2, the
average negative sentiment score prevails with 0.6, thrice the neutral or positive scores. <br>
In comparison, rating of more than 4.5 have an average positive sentiment of 0.4 and an average negative sentiment of 0.3. This would mean that good ratings contain more negative sentiments than bad ratings contain positive sentiment.

Now let's examine the sentiment scoring of sentiment analysis which is done using the
pre-trained model twitter-XLM-roBERTa-base by taking a look at a few examples.

![image-center](/assets/images/brns.png ){: .align-center}

Here, the reviews that have the top 5 highest Negative sentiment score is displayed as a
figure. As you can see the reviews include very negative language where disappointment
emotions are displayed extensively.

![image-center](/assets/images/brps.png ){: .align-center}

Here, you can see the content of the reviews does not include negative values when you
concern it with respect to words used in them. However, when you check by its content, you
can see that people reviewed beers with sarcasm. Since the model checked the content of the
reviews without putting effort on detecting sarcasms, the reviews got a high positive
sentiment score.

![image-center](/assets/images/grps.png ){: .align-center}

You can see the good reviews that got high positive sentiment scores and share positive
thoughts about beers they experienced.

![image-center](/assets/images/grns.png ){: .align-center}

We observed that the rating scores we can see in the reviews here are very high, and as in the
example, we observed that the negative sentiment score was high, in which several reviews
that got high ratings were included in sentiment analysis. When we examine the examples to
understand the situation, we can see that they compare them with other bad tastes or praise
the beer they drink using irony. For this reason, the negative
sentences it contains during sentiment analysis or the comparisons made by giving bad
examples to praise the product at the beginning are the main factors that cause this result.


Now, let's check the sentiment results of reviews with extreme ratings, namely ratings under 2 or above 4.5:

![image-center](/assets/images/sentiment_results.png ){: .align-center}

When we look at the results here, we observe that the sentiment prediction of the NLP model
we use about the interpretation with a low rating is mostly negative, while the tendency to
predict positive for high ratings is not the same.
Thus, we observe that while people have a tendency to use negative vocabulary
in reviews where they give low ratings, using positive vocab in high-rated reviews is not as
dominant as the first case, and the use of negative vocabulary in high-rated comments is often
close to positive vocab usage.
This is an important example that shows that people can approach beers from many different
perspectives and that if a beer is bad, everyone can say that it is bad in general, but if it is a
good beer, people can approach a beer to be good from many different angles depending on
their taste or personal preferences. The difference is stark between the past and the present: the memories we have from back in the day are smiling, positive ads that market beer in the best light possible, while in the present, the Internet gives a platform to express what we really think. Truth and opinions can be expressed in different ways, and if we were to analyze reviews for future uses of the dataset, we have to be careful to take the human factor into consideration: less smiling ads, more sarcasm! <br>

# Conclusion

If all this talk about beer hasn't made you feel like drinking one right now, I don't know what will. <br>
We've covered the history of American beer, until its actuality. We've seen that ale dominated back when beer was underground, and that it's now trendy again in the US. We've also covered the lager revolution and seen that the German Belt is as involved in the beer scene as it used to be. We've remembered the dark days of the Prohibition, and we've studied its lasting impact on dry counties' beer opinions. Furthermore, we saw that the local market is still relevant and that inter-state rivalry is still there. Finally, we've shown through sentiment analysis that users' opinions aren't just limited to numbers, and that we have to dig deeper into their review to know what they really think about beer.  

# *References*
[[1]][natives-beer] Beer Studies, North America Protohistory <br>
[[2]][concise-history] "A concised history of America's brewery industry", Martin H. Stack <br>
[[3]][german-stats] "The Lager Revolution in the United States", Seeing The Woods <br>
[[4]][kkk] "The Ku Klux Klan in the 1920s", Bill of Rights Institute <br>
[[5]][prohibition] "These 9 states still have dry counties", 24/7 Wall Street <br>
[[6]][beer-today] Sales Data (U.S. TTB and U.S. Commerce Department, 2022) <br>
[[7]][new-amsterdam] Map of New Amsterdam, 1660 <br>
[[8]][dry-counties] "Wet and dry counties", NABCA Research <br>




[gallup]: https://news.gallup.com/poll/214229/beer-remains-preferred-alcoholic-beverage.aspx"Gallup" 
[natives-beer]: https://beer-studies.com/en/world-history/Birth-of-brewing/Combined-fermented_beverages/North-america-protohistory"Native American beer history"
[concise-history]: https://eh.net/encyclopedia/a-concise-history-of-americas-brewing-industry/
[german-stats]: https://seeingthewoods.org/2018/09/07/the-lager-beer-revolution-in-the-united-states/
[kkk]:  https://www.billofrightsinstitute.org/essays/the-ku-klux-klan-in-the-1920s
[prohibition]: https://247wallst.com/special-report/2019/12/12/states-that-still-have-dry-counties/#:~:text=Today%2C%20there%20are%2083%20counties,have%20long%20preceded%20national%20prohibition.
[beer-today]: https://www.brewersassociation.org/statistics-and-data/national-beer-stats/
[new-amsterdam]: https://viewing.nyc/the-original-city-map-of-new-amsterdam-circa-1660/
[dry-counties]: https://www.nabca.org/sites/default/files/assets/publications/white_papers/WetDry%20Counties.pdf
[nlp]: https://huggingface.co/cardiffnlp/twitter-xlm-roberta-base-sentiment?text=ADA+is+great