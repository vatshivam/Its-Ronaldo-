# Its-Ronaldo-
Data Analysis on stats of Cristiano Ronaldo available on Kaggle.
In each file, different insights about the game behaviour of Cristiano Ronaldo is extracted out.
Language Used: Python
Data: https://www.kaggle.com/kerneler/starter-cristiano7-43250438-1. Following are the main points covered by each file having the code. There is no as such special reason to do this, i like Cristiano Ronaldo as an idol. So that is why, I attempted to do the same. 

# Prediction
Code for prediction (whether there will be a goal or not) is present in this repo(prediction.ipynb). The code is under constant development. I regularly update and try new methods for prediction to get a better accuracy score. You will find implementations of different machine learning algorithms for the same. Have also covered deep learning algorithms in it.    

# Find Best Season:
>>In this file, I tried to figure out what is the best season out of all the season given in the data.
>>The same is represented using a bar graph showing number of goals scored in each season.

# Shots Per Season:
>>Don't go by the name. Its not telling us number of shots attempted. But turns out, we can analyse and compare the goals and shot behaviour per season.
>>We can see this by looking at the third plot.
>>In that plot the x axis is the seasons as usual and the y axis is the ratio of goals to shots. That is,it is the ratio of success rate of shot attempts resulting into goals. 
>>We can easily interpret that the plot curve moving upwards signifies greater gaol conversoin rate.

# Remaining Time Vs. Shot Distance
>>Its the most intuitive part of my analysis.
>>Shot distance is the distance measured from the goal to the player's position where it takes the shot.
>>Its quite palpable that with hardly 10 minutes remaining and to do a comeback in the game, any player might fancy its chances to strike a goal from a larger distance relatively.
>>This behaviour is recorded via a line plot.
>>In the plot we can see a general trend that as the remaining number of minutes decreases, the distance of shot increases.
>>Do check the code for better insight.

# Area of Shot and Goal
>>This is the last set of the sequence of data interpratations of this project.
>> In this, I tried to check whether there is a pattern of goal scoring. Is there a possibility that maximum number of goals in a season are coming only from a specific areaof the field.
>>To visualize this, I plotted a pie chart for each season.\
>>In each pie chart, the segments are represented as area of the field from which the shot is taken and is converted to a goal.
>>If one looks at the pie charts, it will easily notice that, for every season a majority share of goals comes from a specific area.
