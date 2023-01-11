# Twitter-Hate-Speech-Dataset

**Important Note: All of the User IDs Are Anonymized. No Personal Info Is Disclosed in the Datasets Publicized Here.**

In this repository, we release the *Hate Speech Dataset* used in our paper *Hate speech on online social media through the lens of language and behavior: Analysis and prediction*. 

our dataset consists of tweets belonging to two groups of users: 
(1) *hate* group who  posted content promoting hate speech targeted towards Anti-Asian Hate during the COVID-19 Crisis
(2) *control* group who either posted general ideas about COVID-19 and China/Asians or posted counter hate speech to support Asians

We collect tweets between 15 Jan 2020 and 26 Mar 2021. We use Twitter API to collect their timelines i.e. most recent 3,200 tweets. We use the user’s timeline posts up to the first hate tweet for analysis (only users with at least 100 tweets). For control users, we sample such a date from a normal distribution having mean and variance of first hate posts of Hate data.

