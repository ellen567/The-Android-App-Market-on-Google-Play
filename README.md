# The-Android-App-Market-on-Google-Play

## Project Description

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this project, you will build an automatic credit card approval predictor using machine learning techniques, just like the real banks do.

The dataset used in this project is the Credit Card Approval dataset from the UCI Machine Learning Repository.

## Topics

- Data Manipulation
- Machine Learning
- Importing and Cleaning data
- Applied Finance

## Dependencies 

- `Pandas`
- `Matplotlib`
- `Seaborn`

## The structure of this notebook is as follows: 

1. Load `apps.csv` and clean data
2. Explore the market share for each app category by plotting a barplot.
3. Explore distribution of app ratings by plotting a histogram.
4. Explore how the size and price can effect app rating.
   - `sns.jointplot()`

5. Explore the relationship between category and app price.
   - Plot price vs. category stirpplot
   - List the apps greater than $200. Most of which are  'junk' apps.
   - Filter out 'junk' apps by selecting apps priced below $100, and make a stripplot again.
6. Explore the popularity of paid apps vs. free apps by boxplot.
   - Paid apps have a relatively lower number of installs than free apps.
7. Explore the sentiment difference between paid apps vs. free apps by boxplot.
   - Free apps receive harsh comments while paid apps never get extremely negative comments
   - The median polarity score for paid apps is a little higher than free ones.
