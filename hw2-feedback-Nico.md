### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Fantastic job on this! You are getting quite handy with python/pandas, and you did a great job finding new packages to use like scipy for the normality test! Also, your answers were very precise and well worded. :D I don't have much advise thus far! Just keep on playing with Python and try implementing more of the techniques we use in class.


**Some Notes**

* Regarding your analysis plan, you should probably include what models/modeling techniques you think you should use. Considering we haven't gotten into it yet, this is more than okay to not include. However, typically when you write out your analysis plan, you include data cleaning, data manipulation, some analysis, and then modeling techniques to find, in this case, the relationship between Admission and Prestige!

**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html
