# My experiences with Python and SQL






Besides my jobs, I have had some serious experiences with both Python and SQL. Including some projects I was collaborating with and some national/international contests I have participated in. I have written a broad explanation for you, feel free to ask for more detail for each of them.


## Career

### My current position; Guest researcher at Nijmegen

My current job as a researcher is more related to mathematics rather than computer science. I am working on finding the root of the preferential attachment networks which are important in social network analysis due to their power law degree distribution. The problem itself is abstract and require probabilistic methods to solve, however, I am using Sage and Matlab for implementation to get ideas.

### Previous position; Data analyst at Café Classic

As a data analyst my job was acquiring data of users activities and analyze them. Mainly for fraud detection and finding fake IDs but I also provided a model for promotion of users. I was using ad-hoc analysis on users activities (likes, posts,…) and also some basic NLP methods to find fake users. Since the size of data was affordable, I just used Pandas for preprocessing and analyzing data.




 
## Projects

### Oil well startup
It is a startup concerning private oil well companies. One of the objectives of the application is to automize reporting system of drilling machines. My job was to design a model to detect the status of the system based on data recieving from sensors.
I used Python to create an ad-hoc model specific for them after learning basics about extraction process.

### Smuggling detection
I helped a project in *Iran Customs Administration*, as an anomality detector. The goal was to find smuggling based on data measured at the border and data claimed by the merchants. The data was very messy since their reporting system was unorganized. I used SQL for preprocessing and Python for analyzing. The project was not very successful due to lack of useful data and real world obstacles.
 
## National competitions

### Alibaba travels contest
It was a data mining contest with a rather small data (300 MB) of flight bookings in *Alibaba.ir*. Since the size of data was affordable I only used Pandas to manipulate it. For prediction, I used *lightgbm regressor* (which is a boosting algorithm) in Python to build a model for prediction the number of bookings in each day of the current year based on the data from previous years. I achieved the 1st place.

### DECA, big data contest
It was a national data mining contest operating on 10 GB data of push notification. The mission was to predict which user likes which kind of notifications. The data was real and super messy distrusted in several files. I used SQL to prepare data and Python to implement a *deep neural network* for classification. I achieved the 6th place.

 
## Kaggle competitions
 

### Newyork taxi fare prediction
It is probably the best success I have had since it was an international competition with high level competitor. The mission was to predict the fee of taxi rides in Newyork city based. The data was about 2GB and I again used *lightgbm regressor* to predict the price and *neural network* for classification of outliers. I reach 25th place which is in top 2%.

### Quick draw
It was a challenging competition and the goal was to label doodlings drawn by various people. The simplified version of data which I worked with was about 8 GB. Data requiered lots of preprocessing since only corners of paintings was given. I used *convolutional neural network* in Python to implement a predictor. Besides the *convolutinal network* I used statistics of the paintings to have an auxilary network. I placed in top 30% which is not a good result but I learned a lot in this competition.

