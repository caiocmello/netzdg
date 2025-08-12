# NetzDG on Twitter: a study of debates on the German anti-hate speech law

This repository for NetzDG project consists of notebooks written in Python to perform the following tasks on the data:
1. NetzDG_Analyser: Generates a list of n-grams (unigrams, bigrams...). You can search for terms mentioned by particular users or clusters; or by all accounts included in the dataset. It also allows for temporal analysis, filtering texts by date of publication.
2. NetzDG_URLs_v2: Produces lists of the most mentioned URLs in the dataset as well as the most mentioned web domains. It's also possible to filter data and look at specific websites to see in which context they are mentioned. Data used here includes retweets. 
3. NetzDG_colours: This notebook has been created to analyse orange, red, green and grey clusters. It reproduces the N-grams approach used in 'NetzDG_Analyser'. It also produces charts on the temporal distribution of tweets, as well as likes and retweets over time. 
4. NetzDG_content: Allows for content analysis. It displays tweets mentioning specific words, showing the text that precedes and text that follows the searched word. It produces word clouds with the most mentioned words in texts where the searched word appears. Data can also be filtered by cluster.
5. Topic_modelling_NetzDG: Performs topic modeling and displays visualisations. 

