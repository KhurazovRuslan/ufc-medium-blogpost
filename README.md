# Simple EDA of UFC events and weightclasses.

As a huge fan of mixed martial arts, I'm also a fan of mma's biggest promotion, the Ultimate Fighting Championship. And since I started learning data science, I've wanted to get inside some of the numbers UFC has on its statistics website <a href='http://ufcstats.com/statistics/events/completed'>ufcstats.com</a>.
In this project I'll try to answer some questions regarding UFC events and weightclasses:
- Did global pandemic influenced the number of events UFC had in 2020?
- What are the most common destinations for UFC events and has they changed in 2020?
- What is the most exciting weightclass to watch?

In order to do that, I collected data from <a href='http://ufcstats.com/statistics/events/completed'>ufcstats.com</a> and stored it in two .csv files:
- <a href='https://github.com/KhurazovRuslan/ufc-medium-blogpost/blob/main/events.csv'>events.csv</a> - contains information on every UFC event since UFC 2 in 1994
- <a href='https://github.com/KhurazovRuslan/ufc-medium-blogpost/blob/main/fights.csv'>fights.csv</a> - contains information on every UFC fight since UFC 2 in 1994

The code for the analysis is stored in <a href='https://github.com/KhurazovRuslan/ufc-medium-blogpost/blob/main/for%20blogpost.ipynb'>Jupyter notebook</a>.

The notebook uses python 3.8.6 and the folowing libraries for web scraping and analysis:
- beautifulsoup 4.9.3
- pandas 1.1.0
- matplotlib 3.3.0

As a result of this project, <a href='https://khurazovruslan.medium.com/its-time-eda-of-ufc-events-and-weightclasses-7156ac802174'>an article is posted on medium.com</a>
