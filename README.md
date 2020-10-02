# Analyzing-Biochemical-Properties-to-Grade-Wine-Quality

Wine  Once viewed as a luxury good, it is increasingly enjoyed by a wider range of consumers. Quality evaluation is often considered in the certification process, and it can also be used to improve wine making. This is done by identifying the most influential factors. Having quality standards also helps price setting. Consequently, the goal of this project is to find out critical variables that significantly affect the quality of wine, and later derive the optimal condition of these variables.

The primary goal is to assess the factors that influence wine quality the most, and then to predict the wine quality using a model represented by these factors.
<ol> <li>The first step of our analysis is to remove the outliers. They may indicate faulty or erroneous data.</li>
<li>Next, the distribution of each variable is analyzed to verify skewness; left-skewed, right-skewed or normally distributed.  A skewed distribution yields improper results for statistical tests. In case of a skewed distribution, a variable is usually transformed using the log, Box-Cox or the square root transform.</li>
<li>The analysis is then progressed with a plot of standard deviation for all variables to find which variables have the most variation and which, the least.</li>
<li>This is followed by an exploration of the pairwise relationship between the variables and wine quality. This tells us about the within-variable relationship changes with quality.</li>
<li>After analyzing the distributions, an evaluation is made to see how variables relate to each other using a heat map. Based on these observations, more detailed explorations is made using scatterplots and 3d plots which helps to narrow down the 3 most important variables necessary for modelling.</li>
<li>Upon narrowing down the 3 variables, we can finally build a model that will be used for predictive analysis. Because the model may not necessarily perform best using only the most essential factors affecting wine quality, it is imperative to include a few other underlying factors in order to make the model more robust for predictive analysis, such that it generalizes data at its best.</li>
</ol>
