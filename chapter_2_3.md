# Choosing an Effective Visual (part 3) - Things to Avoid

Here are some specific graph types that you should avoid:
1. Pie charts
2. Donut charts
3. 3D
4. Secondary y-axis


## 1. Pie Charts (are evil)
- Remember that the human eye is not good at ascribing quantitative value to two-dimensional space (i.e. pie charts are hard to read)
- When segments are close in size, it's difficult to tell which is bigger at a glance. Even if you add data labels, the visual is not worth the space it takes up.
- Instead of a pie chart, consider using a horizontal bar chart. This will enable people to see not only which segment is the largest, but also how incremntally larger it is than the other segments.
- This isn't to say that there are no usecases to use a pie chart. But it generally isn't the best choice out of the other charts.
- 
![image](https://github.com/alexlee2000/storytelling_with_data/assets/43845085/d2f00a2c-847f-4cbb-9aa2-d596f351008a)


## 2. (Donut use) Donut Charts 
- With Pies we ask the audience to compare angles and areas.
- With donuts, we ask the audience to compare one arc length to another arc length.
- Either of these are often more difficult for the audience to ascribe quantitative value.

![image](https://github.com/alexlee2000/storytelling_with_data/assets/43845085/8fbfe6ed-a0ef-43bc-a377-1104e78fb147)


## 3. (Never use) 3D
- Never use 3D, unless you are actually plotting a third dimension
- 3D skews our numbers, making them difficult or impossible to interpret or compare
- Adding 3D introduces unecessary chart elements which are distracting.
- Furthermore, graphing applications do strange things when it comes to plotting in 3D (e.g. in Excel, the bar height is determined by an invisible tangent plane intersecting the corresponding height on the y-axis. This makes the bar height look smaller than it actually is)

![image](https://github.com/alexlee2000/storytelling_with_data/assets/43845085/b4fe12e2-ca62-41e8-99ce-07195bfe20ef)


## 4. Secondary y-axis (generally not a good idea)
- Sometimes it's useful to plot data that is in entirely different units aginst the same x-axis. This often gives rise to the secondary y-axis (another vertical axis on the RHS of the graph)
- Interpreting a graph with a secondary y-axis will take some time and reading to understand what is going on. So instead of showing the secondary y-axis, consider one of the two approaches:
  1. Label the data points that belong on this axis directly (this will put more attention on the specific numbers) OR
  2. Pull the graphs apart vertically and have a separate y-axis for each (both along the LHS), leveraging the same x-axis across both (this will put more focus on the trends).

![image](https://github.com/alexlee2000/storytelling_with_data/assets/43845085/96866805-e2b5-4459-a314-7f7406b7cd7a)

Another 3rd hidden option is to use colour to help distinguish which y-axis refers to which bars/lines (i.e. use blue for LHS y-axis title and blue for the bars + use orange for RHS y-axis title and orange for the line). However, this is not recommended as colour can typically be used more strategically.

Furthermore, when you display two datasets against the same axis, this implies that a relationship may or may not exist. This is something to be aware of when determining whether this is an appropriate approach in the first place.


## In Closing - What is the right graph for my situation?
In many cases, there isn't a single correct visual display; rather often there are different types of visuals that could meet a given need. However, you should choose a visual based on whichever will be easiest for your audience to read/understand. To test how easy a visual is to read, create your visual and show it to a friend or colleague and ask them to articulate the following as they process the information:
1. Where they focus
2. What they see
3. What observations they make
4. What questions they have

