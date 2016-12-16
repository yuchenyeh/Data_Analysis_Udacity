Summary - 
This visualisation helps to understand surviving demographics for the Titanic incident that happened in 1912. 
Two different categorical variables, Sex and AgeGroup, are combined to see how the survival rate is subdivided. 
It shows the female, in general, survived better in this incident. Also, it seems the younger had a better chance of surviving.

Feedback-
First version
http://bl.ocks.org/yuchenyeh/f1b3f777e5dd49fa8cf99754be641e2c (including original visualisation and HTML files)
I have consistent feedbacks from three people that it is quite hard to interpret the visualisation.
Forum mentor George said: it is a modern visualisation, but-but it is hard to see how the splits between 'perished' and 'survived.
My friend Emily said: it is not easy to understand wich demographic survived better with so many relationship lines. 
My colleague Tim said: I don't understand what the percentage represents in the tooltip?

Second version
http://bl.ocks.org/yuchenyeh/6eafebaff97c8cd2c449d89b6cc972c6 (including original visualisation and html files)
Not clear about the meaning of the green and red encodings as well as the value on the y-axis.

Design - 
I first used parasets to present to data, as the feedbacks pointed out it is not easy to have crystal clear understanding of the visualisation.
I then decide to use Mekko Matrix from dimple.js to present the survival rate with each combination of sex and age groups. 
Mekko Matrix is great at presenting multi variables, and colours are used to correspond to indicate survival (red for perished and green for survived).
Bar chart with the percentage on the y-axis is used to display the survival rate.

Resources - 
http://dimplejs.org/advanced_examples_viewer.html?id=advanced_matrix