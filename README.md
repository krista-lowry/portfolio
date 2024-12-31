# Welcome to My Portfolio!

Here you will find my recent projects showcasing my technical and business acumen in data anaylsis, strategic planning, and client presentations. 

## Project 1: Identifying User Segments and Predicting Conversions

This project showcases my ability to perform in-depth data analysis using R code, transform findings into visualizations in Tableau, and offer data-driven recommendations to optimize marketing and CRO strategies.

#### Summary 
Our client wants to identify key predictors of whether a user will convert (purchase a product) so they can optimize their marketing campaign strategies and website conversion funnel. 

In particular, they want to understand:
- optimal target audience
- best time of year to ramp up campaigns for maximum ROI

In addition to this analysis, they also want an operational dashboard to monitor performance as they start fine-tuning their strategies based on these findings.

#### There are three deliverables:
1. [Data exploration and anaylsis using R code in Jupyter Notebooks](https://github.com/krista-lowry/portfolio/blob/main/r-code-markdown.ipynb)
2. [Tableau dash for monitoring performance](https://public.tableau.com/app/profile/krista.lowry/viz/OnlineShopperIntent-TableauDash/Performance){:target="_blank"}

#### Data Exploration and Analysis
In this section of the project, I conducted exploratory data analysis, data cleaning, and evaluated 4 machine learning models before deciding that Logistic Regression was the optimal model to predict key features of conversions. Although the fit was not particularly strong, the accuracy and specificity was such that we could identify patterns in what features may be indicative of conversion.

These key features were: Returning Users, Special Days, Duration spent on product pages, and specific months of the year surrounding holidays. In other words, if a user has visited the client's site multiple times and is visiting during a holiday period, they are more likely to convert. 

This conclusion is not ground breaking: it stands to reason that a user who is familiar with the product will visit on a holiday during a special promotion to purchase the product. The more important information this model help us understand is what's *not* important. Noteably, operating system, browser and region are not key to the likelihood a user will purchase a product.

This insight gives us direction into building an operational and insightful Tableau dashboard for the client as they begin optimizing their campaigns and strategies for the next year.

[Access the Jupyter Notebook](https://github.com/krista-lowry/portfolio/blob/main/r-code-markdown.ipynb)

#### Tableau Dashboard
Given the client's objective to determine the optimal target audience and time of year, I built a Tableau dashboard to show key performance indicator performance month-over-month, during the week and over holiday periods.

The dashboard features indicators of whether a particular segmentation is performing above or below the aggregate average conversion rate, and allows for in-depth analysis of new vs returning visitor performance through filter parameter selection.

Although we know that operating system, region and browser are not particularly important to constructing an optimal target audience, we can use these datapoints to construct a view of where the user is coming from and what technology they are using. The user segments tab shows sessions and conversion rates by each dimension and indicates where conversion rates are falling below average, so that the client can investigate and resolve any potential user painpoints. 

Next steps: 
- Identify and present specific strategies the client can take in the next holiday season to maintain and improve conversion rates in their key returning uesrs market, and how they can increase conversion volume from new users.

[Access the Tableau Dashboard at Tableau Public](https://public.tableau.com/app/profile/krista.lowry/viz/OnlineShopperIntent-TableauDash/Performance){:target="_blank"}