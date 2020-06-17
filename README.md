# Personality-Prediction-using-IBM-Watson
### Using IBM-Watson PersonalityInsightV3 predicted the likeliness of a wide variety of Personalities based on a Instagram uesr's post captions.

## Data Collection :
### Steps to reproduce :
1. Installing dependencies :\
```pip install selenium```\
Download [Chrome Driver](https://chromedriver.chromium.org/downloads) and place the .exe file in program files.
2. Wrote a python script [instagram-caption-scrapper.ipynb](instagram-caption-scrapper.ipynb) which scrapes an Instagram User's Post Captions (the number of posts to be scraped can be varied) then after cleaning the data-collected , a csv file and text file is generated.
3. Login need not to be done for its execution.

## Personality Prediction :
### Steps to reproduce :
1. Login to your [IBM Cloud Account](https://cloud.ibm.com/).
2. From 'Catalog' , select 'AI / Machine Learning' and choose 'Personality Insights'.
3. Generate API_KEY and URL.
4. Open terminal and enter :
  ```pip install watson-developer-cloud```
5. After placing your API_KEY , URL , and the text (on which the personality will be predicted) in the appropriate cells , execute [Personality-Prediction-IBM-Watson.ipynb](Personality-Prediction-IBM-Watson.ipynb)
6. A .csv file is generated displaying the probabilities of a wide range og personalities.
