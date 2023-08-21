<h1 align="center">Problem Statement</h1>
Recent years have witnessed a surge in the number of internet savvy users. Companies in the financial services domain leverage this huge internet traffic arriving at their interface by strategically placing ads/promotions for cross selling of various financial products on a plethora of web pages. The digital analytics unit of Best Cards Company uses cutting edge data science and machine learning for successful promotion of its valuable card products. They believe that a predictive model that forecasts whether a session involves a click on the ad/promotion would help them extract the maximum out of the huge clickstream data that they have collected. 

You are hired as a consultant to build an efficient model to predict whether a user will click on an ad or not, given the following features:
Clickstream data/train data for duration: (2nd July 2017 – 7th July 2017)
Test data for duration: (8th July 2017 – 9th July 2017)
User features (demographics, user behaviour/activity, buying power etc.)
Historical transactional data of the previous month with timestamp info (28th May 2017– 1st July 2017). This data contains actions (views/interest registered) taken by the user historically on the product page via an ad or other sources
Ad features (product category, webpage, campaign for ad etc.)
Date time features (exact timestamp of the user session)


<h2 align="center">Motivation</h2>

"AdClickPredictor" is a repository exploring online ad engagement prediction using machine learning. It provides a dataset with user attributes and interaction outcomes, guiding users through preprocessing, modeling, and performance assessment via a comprehensive Deepnote notebook. 

The main motivation behind the project is "Targeted Advertising." At its most basic, targeted advertising can just mean that ads are chosen for their relevance to site content, in the assumption that they will then be relevant to the site audience as well. Online advertisers can use different methods to target a particular advertisement on the user based on its traits. Most companies do this as part of social media platforms like Facebook, LinkedIn, etc. However, many times the process goes wrong, and the advertisement does not reach its target audience because it is sent out without actually understanding the probability of the occurring click.

<h3 align="center">Public and Private Split</h3>
Test data is further randomly divided into Public (30%) and Private (70%) data.
Your initial responses will be checked and scored on the Public data.
The final rankings would be based on your private score which will be published once the competition is over.

American Express hosted a machine learning hackathon (https://datahack.analyticsvidhya.com/contest/american-express-amexpert-2018/). We have provided by data of clickstream of 6 days from 2 July 2017 to 7 July 2017. We have to predict depending upon the data wether a session will result in a click or not.