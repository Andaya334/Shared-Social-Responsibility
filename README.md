# Shared-Social-Responsibility
Hypothesis Testing


### Subject: 
Shared Social Responsibility - A Field Experiment on Pricing Strategies in an Amusement Park

### Introduction:
The amusement park industry constantly seeks innovative ways to maximize revenue while enhancing customer engagement. In this context, our company conducted a field experiment at an amusement park, investigating how different pricing strategies for photographs sold after a roller coaster ride affect consumer behavior and sales. The photos, taken during the ride, were offered under four distinct pricing conditions: a flat-rate price, a flat-rate price with a charitable donation component, a name-your-own-price (NYOP) model, and an NYOP model with a charitable component. These strategies were designed to explore how consumers respond to fixed and flexible pricing models, and whether introducing a charitable cause influences purchasing decisions.

The charitable partner for this experiment was a nationally recognized patient-support foundation, adding a social responsibility component to two of the pricing conditions. The goal was to assess not only the profitability of each strategy but also the broader societal impact, considering both the amusement park's profits and the contributions to charity.

### Flat Rate Pricing

Here, we are using the "Sales.csv" Dataset: This dataset contains the number of photos sold, the number of riders, and the total merchandise revenues for each of the four conditions. Each condition was in place for 2 days (two rows of data) except for the last condition, NYOP Charity, which was in place for 3 days.

It has the following variables: 
1. Condition = A factor with four levels, matching each of the possibilities described above: FR, FR Charity, NYOP, and NYOP Charity
2. NumberSold = The total number of photos purchased by consumers on a given day under the condition described
3. Riders = The total number of riders placed into the condition on a given day under the condition described
4. MerchandiseRevenues = Ancillary revenues related to merchandise purchased by riders at a location adjacent to the ride. Revenues are in US dollars.

### NYOP Pricing
Here, we are using the NYOP.csv datast: This dataset contains more specific information related to the NYOP and NYOP Charity conditions. Each row represents the purchasing behavior of a rider who made a purchase. Information on the condition of the rider, the number of photos purchased, and the price chosen by the rider have been collected.

It has the following variables:
1. Condition = A factor with two levels, NYOP and NYOP Charity, capturing any rider who was in one of the two Name Your Own Price conditions
2. Number = The total number of photos purchased by a given rider
3. Price = The price chosen by the rider and paid in US dollars.

### NYOP Part-2

A. Load “NYOP.csv”. Create a variable called UnitPrice which takes the variable, Price, and divides it by Number. After doing so, next change the type of the variable, Number, to a factor variable.

B. Visualize both Price and UnitPrice against the factor variable, Number by creating box plots and interpreting them.

C. Determine the average unit purchase price for both the NYOP and the NYOP Charity conditions. Does the difference seem small or substantial? Formulate a statistical test to determine if these two average unit prices are different.

D. What are your null and alternative hypotheses?

E. Use the pyrsm library to perform the test computation (Compare means). What can you conclude? What is the likelihood you have made either a Type I or Type II error based on your conclusion?

F. Use filtering to investigate the difference in means for people that purchased 1 picture. Similarly, do the analysis for the group that purchased 6 pictures. Discuss your observations.

G. If you do the analysis by hand for the group that purchased 6 pictures are your results the same as those produced above? Why or Why not?

### Economics

A. The unit cost of making a photo is $1.20. Compute the average daily profit under each of the four pricing strategies.

B. Which strategy is the most profitable? What is the ranking of the strategies in terms of profits?

C. Now think about the additional value created by the FR Charity and NYOP Charity conditions. Rather than focusing only on profits to the theme park, let’s talk about total profits to society which should include both the theme park and the charity that benefits. What is the ranking of societal profits in this case?

D. How much additional societal profit does the leading strategy generate over the others over the entire year (assume 365 days)?

E. Are merchandise sales a concern?

This case intends to demonstrate the effectiveness of hypothesis testing to find valuable insights.