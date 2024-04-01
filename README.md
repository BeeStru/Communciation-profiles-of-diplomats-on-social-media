# Communciation profiles of diplomats on social media
Keywords: Data collection, wrangling, visualisation, sentiment analysis, correspondence & cluster analysis.

## Project overview
This project analysed the content of tweets posted by Chinese diplomats on the platform X (Twitter) over
a 5-year period. The goal was to identify distinct profiles of their communciation behaviour by combining manual content analysis and statistical analysis. 

## Research gap and motivation
Starting 2017, the number of Chinese diplomats on foreign social media platforms have exploded. Researchers of Chinese politics know to link this to the country's leadership initative to "tell CHina's story well" as part of the "peaceful rise" strategy. 

Dubbed ‘wolf warrior diplomacy’, journalists have so far mostly just looked at one trait of the diplomat's communicaiton behaviour: a high level of assertiveness. Yet, we are lacking a data-driven analysis of this observation, and more general lack any further insights into their communication behaviour.

In an exploratory effort, we aimed to answer the following questions
(1) what topics, locations, functions, and level of assertiveness were most prominent? 
(2) what were the distinct communication profiles that the associations between these features reveal?

## The data analysis
The data came from a list of 187 diplomats, who produced roughly 1 million tweets in the period from 1
January 2017 to 1 July 2022. Full details will be publicly available in a forthcoming publication by Sullivan,
Struve, and Wang (2024). I focused here on original tweets and quotes, which total 271,787 tweets. 

Existing research led us to hypothesise that the majority of tweets are highly assertive. In an exploratory effort, we added variables regarding the topic, location and communication function for further insights into the content and style of the diplomat’s communications. So, the coding framework we developed has the four main
variables: topics, location, function, lv of assertiveness (with 15, 17, 7, and 3 coding options, respectively).

In R, I computed a sentiment score for each tweet to aid the manual content analysis. Then, following completion of coding, I answered the questions using data visualisations, multiple correspondence analysis and hieararchical clustering.
