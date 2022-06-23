# Data Visualization 

> susmitha chereddy email:schereddy2371@floridapoly.edu. 

## Mini-Project 2

In this project, we are trying to produce three different charts using 3 datasets.

- interactive plot using fifa18 dataset : here we are trying to see if age group has any effect on the potential, shot  and passing capabilities of the player.
	fifa18 dataset contains 17076 rows and 40 columns depicting different attributes of the player like stamina,potential, ability to kick, pass and display aggressiona nd balance.
		Summary of observations:
		1. I could say the shot_power and long passing are highly correlated and it makes sense since you need shot_power for passing the ball long.
		2. I could also say that: Although there is enough correlation between standing tackle and potential, we see enough enough data points to say that this correlation is not strong enough.
		3. Also, another finding is that Age has very effect on power, passing, Tackle and potential of players.
		
- spatial visualization using florida lakes dataset: plotting to visualize the number of lakes in state of florida and especially the polk country if the name lakleand has any relation to the number of lakes here
	Florida Lakes Dataset contains: 4234 rows and 7 columns.
	a.PERIMETER
	b.NAME
	c.COUNTY
	d.OBJECTID
	e.SHAPEAREA
	f.SHAPELEN
	g.geometry
		Summary of observations:
		1. we could say that although the data set does not give the shape of Florida, visualizing all the lakes gives a rough shape of Florida which says that coast of florida have a lot of lakes. So many that it gives the shape of the cost.
		2. Also, after visualizing the the lakes in Polk county, we could see how lakeland got it's name.
		
- Visualization of the model on Housing dataset: here we are visualizing the prediction of House prices using Housing dataset and see how different variables affect the resultant prices
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
	
	Summary of observations:
	
		1. Number of FLOORS and HALF_BATH in a Home are highly significant in predictng the price of the home in the respective order.
		2. Co-efficient of LOT_SQFT is almost close to zero, which means it is very less significant compared to other variables.