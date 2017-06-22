# Sentiment Analysis using NYTimes
![alt text](https://github.com/swarupmishal/NYTimes-Data-Analysis/blob/master/Extras/newyorktimes-logo.jpg)


# What exactly the Data is?
### Data using Article Search api
###### Dataset1: 
Article Search dataset for Obama and Trump gathered using api-key. I have collected about 120 json files related to both Obama and Trump, each consisting about 10 articles. So basically 2400 articles were used in all for analyzing the data.

###### Dataset2: 
Community dataset regarding Presidential Election using community api-key. Data was collected for the month of November from 11/10/2016 to 11/30/2016. For this question, I am trying to analyze sentiments of users after the results of Presidential Election were declared on 9th of November, 2016.

# How can one obtain the Data?
All the information for downloading the data is provided in here:

http://developer.nytimes.com/

1. You would need to create an API key.
2. Use request or beautiful-soap library to download the data. (No other library or crawler allowed).
3. Store the data in your local machine.


# How is the Data stored?
The data is stored in the form of json files.


# Analysis:

###### Analysis1:
Here I am trying to analyze sentiments of authors of NYTimes. For this analysis I have used the article search api to get data for President Donald Trump and former President Barrack Obama
![alt text](https://github.com/swarupmishal/NYTimes-Data-Analysis/blob/master/que%5B2%5D/ana_%5B2%5D/1.png)

###### Analysis2:
Here I am trying to analyze sentiments of people after the results of Presidential Election were declared on 9th of November, 2016
For this analysis I have used community api to get data from 11/10/2016 to 11/30/2016


# Conclusion:
###### Conclusion1:
We can conclude that NYTimes do publish articles which are more neutral in case of Obama. Also we can see that NYTimes.com do publish a lot of negative articles in case of Trump. From the graph we can also analyze, in case of positive articles, when 240 positive articles about Trump were published, 274 positive articles about Obama were published. While in case of negative articles when 277 negative articles regarding Obama, a considerable amount of 397 negative articles
were published about Trump. Thus, we can conclude that most of the authors of NYTimes of the articles write in favor of Obama.

###### Conclusion2:
We can conclude that the number of users on NYTimes.com, not happy with the result of the presidential election are more. As we can see the number of negative comments is more than the number of positive comments.
