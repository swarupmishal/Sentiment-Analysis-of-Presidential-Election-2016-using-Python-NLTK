# Sentiment Analysis using NYTimes

![alt text](https://github.com/swarupmishal/NYTimes-Data-Analysis/blob/master/Extras/newyorktimes-logo.jpg)


# What exactly the Data is?
### Data using Article Search api
Dataset: Article Search dataset for Obama and Trump gathered using api-key. I have collected about 120 json files related to both Obama and Trump, each consisting about 10 articles. So basically 2400 articles were used in all for analyzing the data.

# How can one obtain the Data?
All the information for downloading the data is provided in here:

http://developer.nytimes.com/

1. You would need to create an API key.
2. Use request or beautiful-soap library to download the data. (No other library or crawler allowed).
3. Store the data in your local machine.


# How is the Data stored?
The data is stored in the form of json files.


# Analysis:
We can see when the meeting emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20meeting%20emails%20sent%20over%20time.csv)

We can see when the casual emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20casual%20emails%20sent%20over%20time.csv)

We can see when the core emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20core%20emails%20sent%20over%20time.csv)

We can see when the process related emails were sent [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Distribution%20of%20process%20emails%20sent%20over%20time.csv)

We can see list of emails Jeffrey Skilling interacted the most with [here.](https://github.com/swarupmishal/Exploratory-Data-Analysis-of-Enron-Scandal/blob/master/que%5B1%5D/ana_%5B1%5D/Skilling%20interaction%20email%20frequency.csv)

# Conclusion:
From the outputs seen above we can understand number of meeting related emails, casual emails, process related emails and core business related emails and when they were sent. We can analyze that most of the enron emails consisted of Business Process. Casual meeting related emails were more than official meeting, which can be a result of fraudulent activities carried on within Enron. There were moderate number of core business related emails sent. If we observe carefully there is a huge spike in core business emails towards the end, maybe to hide their fraudulent activities. 

Also we have analyzed top 10 emails whom Jeffrey Skilling, the CEO of Enron, who was involved in the scandal interacted with. Further investigation can be carried out on these emails.
