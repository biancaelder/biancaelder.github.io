If we think about Billboard’s rankings as a benchmark for what’s popular at the moment, it can be an extremely valuable source of information. This week we’re using data from the 2000 Billboard Hot 100 to explore what makes a song a hit. While there are many approaches one can take with a dataset like this, I chose to analyze the relationship between song length and the length of time on the chart.  

In this dataset there are 11 songs between three and four minutes long , 154 songs between three and four minutes long, 125 songs between four and five minutes long, 20 songs between five and six minutes long, four songs between six and seven minutes long, and three songs over seven minutes.


![time-dist](https://github.com/biancaelder/GA-DSI/blob/master/projects/projects-weekly/project-02/images/time%20distribution%20.png?raw=true)

I started out hypothesizing that tracks between three and four minutes would spend more time 
on the charts. 

First, I looked at the mean number of weeks on the chart by song length. It looks something like this: 

![length-mean-table](https://github.com/biancaelder/GA-DSI/blob/master/projects/projects-weekly/project-02/images/Screen%20Shot%202016-10-05%20at%208.55.28%20AM.png?raw=true)

While this indicates that songs between three and four minutes tend to stay on the charts longer, in this case the mean may not be a particularly good indicator of the average.  

Here's what the data points look like plotted out: 
![scatterplot](https://github.com/biancaelder/GA-DSI/blob/master/projects/projects-weekly/project-02/images/styled-scatter%20(2).png?raw=true)

While the data points on the plot are varied, the amount of points near the 20 week mark suggest that this is an average number of weeks a track stays  on the chart regardless of song length.

When I calculated the statistical correlation I found that there was only a slight netagtive correlation between these variables(-0.042013726451193133). See here: 

![](https://github.com/biancaelder/GA-DSI/blob/master/projects/projects-weekly/project-02/images/pairplot.png?raw=true)


These findings indicate that there is no significant correlation between song length and the number of weeks a song stays on the chart. While there is a slight negative correlation between these two variables(as shown in the pairplot and correlation coefficient), the p-value (0.20151326296634769) suggests that the relationship is not statistically significant and thus the null hypothesis cannot be rejected.

While you may be able to glean some insight into what makes a song popular looking at other features of this dataset, you would probably need a lot more features (e.g., tempo, demographics, artist information) to distill popular appeal to specific metrics--if that’s even possible. The only sure way to get to the Hot 100 is high sales, airplay, and streams, how an artist gets there is still under consideration.  

