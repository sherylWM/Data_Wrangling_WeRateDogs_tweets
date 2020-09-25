# Project 3 - Data Wrangling of WeRateDogs tweets
This is the third project of the Udacity Data Analytics degree.

Goal: Gather, clean and assess data collected from WeRateDogs twitter account using Twitter's API. Once the data is wrangled, analyze the data to find trends and visualize the data to communicate insights. 

## Details

### Datasets
1. image-predictions.tsv file has been provided by Udacity and contains image predictions alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).
2. twitter-archive-enhanced.csv contains basic tweet data for all 5000+ of the WeRateDogs Twitter account. This dataset is filtered further based on tweets that have ratings only. 
3. tweet_json.txt file is created by querying the Twitter API to collect all information for a tweet by the code provided by Udacity. 
4. Created image_predictions dataframe to store data read from the image-predictions.tsv file.
5. Created tweet_info dataframe to store data read from tweet_json.txt file. (tweet_id, favorites, retweets, created_date attributes were fetched)
6. Created tweets_archive dataframe to store data read from twitter-archive-enhanced.csv file.

wrangle_act.ipynb file was created to perform data wrangling (Gather, Assess, Clean) and later exploratory data analysis. 
Some of the questions answered as a part of the EDA process are:
1. What can you analyze about favorites and retweets and do dog ratings have an impact on these?
2. Was there any trend in the WeRateDog trends over time?
3. How can we analyze the dog ratings rated by WeRateDogs in this dataset?
4. How can we analyze dog stages in the WeRateDogs dataset.

Data visualization was performed to display a line chart plot to show the trend of tweets over time.

wrangle_report.html contains all the Data wrangling steps and efforts taken to wrangle the data for exploratory data analysis and data visualization.
act_report.html contains all findings and insights gathered from exploratory data analysis and the data visualization.



