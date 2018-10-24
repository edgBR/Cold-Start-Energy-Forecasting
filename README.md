# Cold-Start-Energy-Forecasting
This project challenging and interesting enough for me. I open to you who wanna join in this project. for having fun guys. money is bonus.

WHAT THIS IS ABOUT

this is a case problem in predicting energy consumption in a competition in Driven Data. for description of the project please check the following site.

https://www.drivendata.org/competitions/55/schneider-cold-start/page/111/

what I got from EDA : 
 ""We have electricity consumption data for each building every hour, there are 1383 buildings where 758 buildings as our training sample are used as input models. The remaining 625 are buildings that we will predict their electricity consumption in the hour, daily and weekly periods""

""Training data provides 28 days of electricity consumption in a matter of hours. while the data test provided a sample of electricity consumption in each building in varying amounts is 4 days, 12 days, etc.""

What do you think is the next step, how will we manipulate the data to be input as our modeling later? in my mind:

first, we can create 3 models in which each data predicts data in hours, days and weeks. the drawback in my opinion this method will make us lose a lot of information because our data will be a little because it is divided into 3 parts.

second we make 1 model to predict the amount of electricity consumption in any period. in my opinion this method is better than the previous metedo.

but why don't we try to try these two methods, just to experiment and have fun. but I will first try the second method because my hypothesis is that the method is better relative to the first.
