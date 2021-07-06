# Problem Statement
Imagine that you have been tasked to optimally allocate funds to 4 different marketing channels: <b>Print, TV, SEO, and Social Media</b> with a total annual budget of $1 million. 

As one can imagine ROI and extent of customer penetration associated with each channel differs and lets assume you know that data already as below -

![Image of Table](https://github.com/Rohit-Karvekar/Blog_Optimization_Modeling_Python_Gurobi/blob/main/channels%20ROI%20and%20Pen_v4.JPG)

The number of customers in the market base is estimated to be around 1.5 million people. Here you want to <b>maximize ROI</b> across all the marketing channels while making sure that the collective customer penetration is at least 1.5 million.

Its wise not to put all the eggs into a single basket and hence the marketing team has come up with following business constraints -
- Conventional Channels (Print+ TV) spend must be at least 40% of the total budget.
- Print cost no more than $100,000.
- The marketing strategy says that Social Media cost should be no more 3 times the SEO costs.
