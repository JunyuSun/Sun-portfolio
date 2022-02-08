# Assignment 3 & 4: Critique by Design
## Step one: Find a data visualization
![Original Visualization](original.png)
source：[Weather Data, Plot, and Code](https://towardsdatascience.com/pgh-weather-data-plot-and-code-19d8e8b670f)
## Step two: Critique the data visualization
This is a graph I found on the web about the distribution of mean temperatures in Pittsburgh, and I found this plot to be highly informative and very interesting. But there are many things about this plot that could also be enhanced. 
The first is that the color of this graph would grab my attention. The color is good from an aesthetic point of view, using an Instagram-like color scheme. But I would question how well this color scheme works when it comes to showing temperature. Using purple to show low temperatures and yellow to show high temperatures is not the accepted by default. 
Then, I would see the "valley" shaped part of each month, which I think is confusing to viewers. People may associate this shape with high and low temperatures, but after looking at the graph for a long time, they will understand that the area of the graph represents the density level of the daily mean temperature distribution over the month, and this graph is a "half violin graph". If I want to improve the graph and retain the density information, I may want to change the graph to a complete "violin graph". 
Finally, I would focus on the X, Y axis coordinates of this graph. Intuitively, the month as a unit of time we would want it to be horizontal; and the temperature we would usually want it to be vertical (like a thermometer). So, I might want to change these axes.
I think this tool is aimed at anyone who wants to know about the climate in Pittsburgh, and from that point of view, the graph somewhat conveys the climate message. But the part about density distribution is probably too specialized and not everyone has the background knowledge to read this graph.
## Step three: Wireframe a solution
I sketch to give my initial solution, and here is my sketch.
![My Sketch](sketch.jpg)
I started by switching the X,Y axis. I used the X-axis to represent the month, which fits the viewer's intuition, and the viewer can compare the temperature of different months horizontally. Then I used the Y-axis to indicate the temperature level. At the same time, I changed the graph to a "violin plot", which retains the density information while avoiding the one-way "valley" shape to distract the viewer's attention. I also changed the color to a gradient of red. I thought the red color would be associated with higher temperatures, while the lighter color would be associated with lower temperatures. Although I also think the color may not be needed at all in this place, since the Y-axis information already expresses the higher or lower temperature. But I think from an aesthetic perspective that this graph should have at least one color, which can also draw viewer's attention.
## Step four: Test the solution

## Step five: Build your solution

<div class="flourish-embed flourish-scatter" data-src="visualisation/8637834"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
