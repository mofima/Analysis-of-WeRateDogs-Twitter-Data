# Wrangle and Analyze Data

## Purpose
> The purpose of this project is to showcase skills in gathering data from different sources, assess the data, clean the data and finally analyze the data. In thi project I used 3 datasets which I gathered from different sources as explained below. There is also a **wrangle_report** pdf that has outlined the steps that I took in gathering, assessing and cleaning the data. There is also an **act_report** pdf that details the insights that I obtained from the analysis of the cleaned dataset.

## Datasets

- The first piece of data to be gathered was the **twitter_archive_enhanced.csv** file. This contained the Twitter archive data from the *WeRateDogs twitter account*. This csv file was already provided for this project. So, I just downloaded it from the Udacity classroom and then imported it into the wrangle_act notebook file as *tweet_archive dataframe*.
- The second piece of data was the **image_predictions.tsv** file containing image predictions. The link to the file hosted on Udacity servers was provided. I used the requests library to download the file programmatically and save it locally. I then imported and read the file into the *image_preds dataframe*.
- The third piece of data was the additional data that was to be queried from the twitter API. Unfortunately, my application for elevated access was denied, so I used the provided **tweet_json.txt** file.


> More information on the steps taken to gather, clean, assess and analyze the data  as well as the detailed information on the analysis of the cleaned dataset are explained in the pdf files named above.
