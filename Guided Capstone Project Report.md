 

# Guided Capstone
## Big Mountain Resort
─
Anjula Epasinghe
### Overview
The Big Mountain resort's pricing strategy has been to charge a premium above the average price of resorts in its market segment. The newly installed lift increased their operating costs by $1,540,000 this season. 

### Goals
Increase profits by 25% by the end of the year.
Specifications

Vermont and New Hampshire might be off on their own a little in the second dimension, although they're really no more extreme than New York and Colorado are in the first dimension.

Summit and base elevation are quite highly correlated. You can also see that you've introduced a lot of multicollinearity with your new ratio features; they are negatively correlated with the number of resorts in each state. This latter observation makes sense! If you increase the number of resorts in a state, the share of all the other state features will drop for each. An interesting observation in this region of the heatmap is that there is some positive correlation between the ratio of night skiing area with the number of resorts per capita. In other words, it seems that when resorts are more densely located with population, more night skiing is provided.

At first, these relationships are quite counterintuitive. It seems that the more chairs a resort has to move people around, relative to the number of runs, ticket price rapidly plummets and stays low. We may be seeing here an exclusive vs. mass-market resort effect; if you don't have so many chairs, you can charge more for your tickets, although with fewer chairs you're inevitably going to be able to serve fewer visitors. Your price per visitor is high but your number of visitors may be lower. Something very useful that's missing from the data is the number of visitors per year.
It also appears that having no fast quads may limit the ticket price, but if your resort covers a wide area then getting a small number of fast quads may be beneficial to the ticket price.
 
 
### Modeling Scenarios
Close up to 10 of the least used runs. The number of runs is the only parameter varying. (The model says closing one run makes no difference. Closing 2 and 3 successively reduces support for ticket price and so revenue. If Big Mountain closes down 3 runs, it seems they may as well close down 4 or 5 as there's no further loss in the ticket price. Increasing the closures down to 6 or more leads to a large drop.)

 
In another scenario, Big Mountain is adding a run, increasing the vertical drop by 150 feet, and installing an additional chair lift. (This scenario increases support for ticket price by $1.99. Over the season, this could be expected to amount to $3,474,638)
If you repeated the last scene with an additional 2 acres of snow-making, made no difference in price. 

