# Data Visualization and Reproducible Research

> Firstname Lastname. 

Learn more about me in my [GitHub profile page](https://github.com/reiminer)


The following is a sample of products created during the _"Data Visualization and Reproducible Research"_ course.  


## Project 01  

In the `project_01/` folder you can find     
1.data/ :about births in US from 2010-14  
2.report/ : HTML report and RMD file for the project  
3.Code and project report along with README and an RProj file.  

This projects aims at summaraizing and analyzing the birth data in US from 2000 - 2014. reports starts with a preliminary understanding of the data with some exploratory analysis and then proceeds towards developing a story about the trend of births in weekdays over weekends. we have used barcharts, density plot and facetwraps to demonstrate the same. In-order to provide additional support, we have provide some mean analysis as well to support our assumption.  

data has [5,479 rows × 6 columns]  
columns:  
 a.$ year         : Factor w/ 15 levels "2000","2001",..:    
 b.$ month        : Factor w/ 12 levels "1","2","3","4",..:     
 c.$ date_of_month: Factor w/ 31 levels "1","2","3","4",..:    
 d.$ date         : Date[1:5479], format: "2000-01-01":     
 e.$ day_of_week  : Factor w/ 7 levels "Sat","Sun","Mon",..:     
 f.$ births       : num [1:5479] 9083 8006 11363 13032 12558 ...    
 
**Sample data visualization:**   

Here is my favorite visualization form the project that explains about density of Births in US . From this graph, we can see the number of babies on the weekend are relatively less compared to weekdays.  
![project1_image](https://user-images.githubusercontent.com/104657112/175607112-82fdd2e0-ee24-4620-9085-ce9b7194e7ab.png)![image](https://user-images.githubusercontent.com/104657112/175607304-7e8e6e29-1202-43b6-9d2d-d2c9b071f6f6.png)





## Project 02

In the `project_01/` folder you can find   
1.data/ :about births in US from 2010-14  
2.report/ : HTML report and RMD file for the project  
3.Code and project report along with README and an RProj file.  

In this project, we are trying to produce three different charts using 3 datasets.  

- interactive plot using fifa18 dataset : here we are trying to see if age group has any effect on the potential, shot  and passing capabilities of the player.
	fifa18 dataset contains 17076 rows and 40 columns depicting different attributes of the player like stamina,potential, ability to kick, pass and display aggressiona nd balance.  
__Summary of observations:__  
		1. I could say the shot_power and long passing are highly correlated and it makes sense since you need shot_power for passing the ball long.  
		2. I could also say that: Although there is enough correlation between standing tackle and potential, we see enough enough data points to say that this correlation is not strong enough.  
		3. Also, another finding is that Age has very effect on power, passing, Tackle and potential of players.  
		
- __spatial visualization__ using florida lakes dataset: plotting to visualize the number of lakes in state of florida and especially the polk country if the name lakleand has any relation to the number of lakes here  
	Florida Lakes Dataset contains: 4234 rows and 7 columns.  
	a.PERIMETER  
	b.NAME  
	c.COUNTY  
	d.OBJECTID  
	e.SHAPEAREA  
	f.SHAPELEN  
	g.geometry  
	
__Summary of observations:__  
		1. we could say that although the data set does not give the shape of Florida, visualizing all the lakes gives a rough shape of Florida which says that coast of florida have a lot of lakes. So many that it gives the shape of the cost.  
		2. Also, after visualizing the the lakes in Polk county, we could see how lakeland got it's name.  
		
- __Visualization of the model__ on Housing dataset: here we are visualizing the prediction of House prices using Housing dataset and see how different variables affect the resultant prices  
	WestRoxbury dataset contains 5802 rows with 14 columns.  
	a.Total_Value  
	b.TAX  
	c.LOT_SQFT  
	d.YR BUILT  
	e.GROSS AREA  
	f.LIVING AREA  
	g.FLOORS    
	h.ROOMS    
	i.BEDROOMS    
	j.FULL_BATH    
	k.HALF_BATH  
	l.KITCHEN  
	m.FIREPLACE  
	n.REMODEL  
	
__Summary of observations:__  
	1. Number of FLOORS and HALF_BATH in a Home are highly significant in predictng the price of the home in the respective order.  
	2. Co-efficient of LOT_SQFT is almost close to zero, which means it is very less significant compared to other variables.  
Find the code and report in the `project_02/` folder.  

**Sample data visualization:** 

_[include your favorite visualization from this project here]_
![project2_image](https://user-images.githubusercontent.com/104657112/175606908-4f63e90c-c3b9-469a-97de-764b5e286b7e.png)


(you can also place your figures in the `figures/` folder and use the `![](path_to_picture)` option to add the pictures here)


## Project 03

In this project we are trying to anlayse the weather data for the city of tampa and also build a wordcloud using a billboards dataset.   
we are tyring to see what are the hottest and coldest months in tampa.  
tampa weather dataset has [367 rows × 6 columns ]   
 $ year         : num [1:367] 2016 2016 2016 2016 2016     
 $ month        : Factor w/ 12 levels "January","February",..:     
 $ day          : num [1:367] 1 2 3 4 5 6 7 8 9 10 ...    
 $ precipitation: num [1:367] 0 0 0.18 0 0 0 0 0.54 0.65 0 ...    
 $ max_temp     : num [1:367] 81 73 61 66 68 67 72 76 78 72 ...    
 $ min_temp     : num [1:367] 70 59 50 49 49 54 56 63 62 56 ...   

For this billboard data, we are trying analyze what the frequently used words on a Billboard.  
Billboard dataset has [100 rows  × 6 coulmns]  
 $ Rank  : num [1:100] 1 2 3 4 5 6 7 8 9 10 ...  
 $ Song  : chr [1:100] "uptown funk" "thinking out loud" "see you again" "trap queen" ...  
 $ Artist: chr [1:100] "mark ronson featuring bruno mars" "ed sheeran" "wiz khalifa featuring charlie puth" "fetty wap" ...  
 $ Year  : num [1:100] 2015 2015 2015 2015 2015 ...  
 $ Lyrics: chr [1:100] "this hit that ice cold michelle pfeiffer that white gold this one for them hood girls them good girls straight "| __truncated__ "when your legs dont work like 

**Sample data visualization:** 
Here a visulization of wordcloud on billboard data
_[include your favorite visualization from this project here]_
![project3_image_2](https://user-images.githubusercontent.com/104657112/175614063-0251c1fe-06ec-479c-9910-329f809d2226.png)

### Moving Forward

_add here a short reflection on what you learned and what you plan to continue exploring in terms of data visualization, data storytelling, reproducible research, and/or related topics_
