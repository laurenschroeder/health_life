# National health spending across the world and life expectancy.

## Summary-
An interactive scatter plot created to show the change in life expectancy and money spent on health over time around the world. The plot interates between 1995 and 2014, showing the PPP expenses per capita in each country and the average life expectancy. The animation shows the general trend of increasing life expectancy and spending on healthcare, with the most significant increases in life expectancy happening in Africa over this time period. Users can hover over data points to see country names and view any specific year using the buttons on the left.

## Design-
I chose to use a scatterplot to show the relationship between health spending and life expectancy. In countries that had higher spending in life expectancy in 1995, spending generally increased at a high rate but life expectancy was more capped. For this reason, I used a logarithmic spending axis to highlight these changes, while showing the significant increase in life expectancy in African countries.

Countries are tagged by continent using a color key. This makes it much easier to observe general trends during the animation. I added year filters at the end of the animation to allow users to investigate specific events during this time span.

## Resources - 
Global Health Expenditure database. World Health Organization. World Development Indicators. World DataBank.

https://www.theguardian.com/world/2014/apr/04/rwanda-life-expectancy-doubles-20-years

## Feedback-

Some feedback (received by four different people) that I've iterated on throughout the design process:

1. Decrease space between title and graph.
  I changed the scale range to leave less of a gap
2. Remove initial screen explaining graph, increase animation speed.
  The animation begins at year 1995 instead of displaying an empty graph with a title and animation speed was increased.
3. Increase size of circles so it's easier to find a country, drop animation (georgeliu1998)
  Radius is increased to make scrolling across circles easier
4. Decrease opacity of data points to see overlap, increase size of buttons to match other text. Add explanatory text at top of visualization.
  
  I chose to keep the animation to show the trend of increased spending and life expectancy over time, especially in Africa.
