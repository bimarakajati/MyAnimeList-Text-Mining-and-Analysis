# MyAnimeList Text Mining and Analysis

This repository contains a text mining and analysis project focused on the anime titled "**Jujutsu Kaisen**." The primary goal of this project is to analyze and gain insights from user reviews on MyAnimeList (MAL) related to Jujutsu Kaisen. However, **the code and methods provided can be adapted for any other anime titles of interest**.

## Data Collection

The data for this project was collected by scraping user reviews from **MyAnimeList**. The web scraping process utilized the **Selenium and BeautifulSoup** libraries in Python. A total of **443 reviews** were scraped to ensure a comprehensive dataset for analysis.

## Exploratory Data Analysis
### Data Overview
| date       | recommendation | review                                                | rating |
|------------|-----------------|--------------------------------------------------------|--------|
| 2021-03-26 | Recommended     | After the ridiculous success of Demon Slayer, ...      | 9.0    |
| 2020-11-06 | Recommended     | *Contains minor spoilers* For me the Shōnen G...      | 9.0    |
| 2021-03-26 | Recommended     | The thing about trends that a lot of people ta...      | 8.0    |
| 2020-11-13 | Recommended     | I rate shit on enjoyment because that is what'...      | 10.0   |
| 2021-04-17 | Mixed Feelings  | This show is as average as they come, personal...      | 5.0    |
| ...        | ...             | ...                                                    | ...    |
| 2023-12-13 | Mixed Feelings  | Objectively speaking, JJK Season 1 is just not...      | 6.0    |
| 2022-08-03 | Recommended     | Jujutsu Kaisen, another shounen anime of the n...      | 10.0   |
| 2022-10-11 | Not Recommended | Ridiculously overrated it’s nothing more than ...      | 1.0    |
| 2023-12-29 | Mixed Feelings  | It took me a while to finish this one.. It's p...      | 5.0    |
| 2023-11-18 | Not Recommended | This anime is so bad it has prompted me to wri...      | 4.0    |

### Recommendation
![Pie Chart](img/rec_pie.png) | ![Bar Chart](img/rec_bar.png)
--- | ---
*Pie Chart* | *Bar Chart*

Jujutsu Kaisen, an anime that debuted with a recommendation from **333 users (75.2%)**, stands out as a highly appreciated choice for the majority of viewers. Meanwhile, **79 viewers (17.8%)** expressed Mixed Feelings about this anime, indicating a variety of responses among its audience. Nevertheless, there are **31 viewers (7%)** who feel that this anime is Not Recommended. Although this figure is not significant, it still reflects a small portion of viewers who may be less satisfied with the elements offered by Jujutsu Kaisen. Thus, the recommendation results for this anime reflect a divergence of responses from its audience.

### Rating
| Rating | Count     |
|--------|-----------|
| count  | 443.000   |
| mean   | 7.819413  |
| std    | 2.004268  |
| min    | 1.000     |
| 25%    | 7.000     |
| 50%    | 8.000     |
| 75%    | 9.000     |
| max    | 10.000    |

Based on the rating analysis for the anime Jujutsu Kaisen, statistical data reveals a total of 443 assessments. The average rating given by viewers is around **7.82**, with a standard deviation of 2.00, indicating the extent of variation in ratings from the average. The lowest rating given for this anime is 1.00, while the highest rating reaches 10.00, reflecting extreme variations in viewers perspectives. In more detail, 25% of ratings are at the level of 7.00 or below, while 50% are at the level of 8.00. Ratings at the third quartile (75%) reach 9.00, indicating that the **majority of viewers give high ratings to Jujutsu Kaisen**. This data provides an overview of the distribution of ratings and how well-received and enjoyed the anime is by its audience.

![Bar Chart](img/rate_bar.png)
The anime Jujutsu Kaisen has received a diverse range of ratings from its viewers. A total of **100 people gave the maximum rating of 10.0**, indicating a highly positive reception towards the quality and storyline of this anime. Furthermore, **100 people gave a rating of 9.0**, suggesting that the majority of viewers consistently give high ratings to this anime. With **84 people giving a rating of 8.0**, the anime continues to receive strong appreciation. However, there is also variation in opinions, where **54 people gave a rating of 7.0, 49 people gave a rating of 6.0, and 28 people gave a rating of 5.0**. The presence of ratings below 7.0 indicates that there are some viewers who may have a more neutral or slightly less satisfied view of this anime. There are also a small number of viewers giving low ratings, such as **4.0, 3.0, 2.0, and 1.0**, reflecting differences in taste among the audience of Jujutsu Kaisen.

### Total reviews by month
![Line Chart](img/date_line.png)
Over the past few months, the anime Jujutsu Kaisen has consistently garnered attention and reviews from its viewers. Based on the data of the number of reviews per month, it is evident that at its **peak popularity in March 2021**, the number of reviews reached a significant figure, hitting 99 reviews. Although this number later experienced a decline, the anime still managed to maintain audience interest with a relatively stable number of reviews in the following months, such as 59 reviews in April 2021 and 27 reviews in May and June 2021. However, over time, there appears to be a more significant decline, with only 4 reviews in December 2021 and 2 reviews in September 2022.

It's important to note that the **number of reviews does not always reflect the quality of an anime** but can provide an overview of how audience interest and interaction evolve over time. Thus, the curve of the number of reviews for Jujutsu Kaisen reflects the journey of this anime in garnering responses from viewers since its launch until the present.

### Top words in every recommendation category
Word Clouds for **Recommended**:

![WordCloud](img/wc_good.png)

Word Clouds for **Mixed Feelings**:

![WordCloud](img/wc_neutral.png)

Word Clouds for **Not Recommended**:

![WordCloud](img/wc_bad.png)

## Notes
```
Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests.
Happy analyzing anime reviews!
```