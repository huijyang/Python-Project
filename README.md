## Project 1: Investing Netfilx Movies and Guest Stars in The Office
### Project Description
In this project, you’ll apply the skills you learned in Introduction to Python and Intermediate Python to solve a real-world data science problem. You’ll press “watch next episode” to discover if Netflix’s movies are getting shorter over time and which guest stars appear in the most popular episode of "The Office", using everything from lists and loops to pandas and matplotlib.

You’ll also gain experience in an essential data science skill — exploratory data analysis. This will allow you to perform critical tasks such as manipulating raw data and drawing conclusions from plots you create of the data. Press play to begin!
### Project Task 1
1. Loading your friend's data into a dictionary
2. Creating a DataFrame from a dictionary
3. A visual inspection of our data
4. Loading the rest of the data from a CSV
5. Filtering for movies!
6. Creating a scatter plot
7. Digging deeper
8. Marking non-feature films
9. Plotting with color!
10. What next?

### Project Tasks 2
Data visualization is often a great way to start exploring your data and uncovering insights. In this notebook, you will initiate this process by creating an informative plot of the episode data provided to you. In doing so, you're going to work on several different variables, including the episode number, the viewership, the fan rating, and guest appearances. Here are the requirements needed to pass this project:

1. Create a `matplotlib` scatter plot of the data that contains the following attributes:

* Each episode's episode number plotted along the x-axis
* Each episode's viewership (in millions) plotted along the y-axis
* A color scheme reflecting the scaled ratings (not the regular ratings) of each episode, such that:
    * Ratings < 0.25 are colored `"red"`
    * Ratings >= 0.25 and < 0.50 are colored `"orange"`
    * Ratings >= 0.50 and < 0.75 are colored `"lightgreen"`
    * Ratings >= 0.75 are colored `"darkgreen"`
* A sizing system, such that episodes with guest appearances have a marker size of `250` and episodes without are sized `25`
* A title, reading `"Popularity, Quality, and Guest Appearances on the Office"`
* An x-axis label reading `"Episode Number"`
* A y-axis label reading `"Viewership (Millions)"`

2. Provide the name of one of the guest stars (hint, there were multiple!) who was in the most watched Office episode. Save it as a string in the variable `top_star` (e.g. `top_star = "Will Ferrell"`).

**Important!**

To test your `matplotlib` plot, you will need to initalize a `matplotlib.pyplot` `fig` object, which you can do using the code `fig = plt.figure()` (provided you have imported `matplotlib.pyplot` as `plt`). In addition, in order to test it correctly, please make sure to specify your plot (including the type, data, labels, etc) in the same cell as the one you initialize your figure (`fig`)! You are still free to use other cells to load data, experiment, and answer Question 2.

In addition, if you want to be able to see a larger version of your plot, you can set the figure size parameters using this code (provided again you have imported `matplotlib.pyplot` as `plt`):

`plt.rcParams['figure.figsize'] = [11, 7]`

**Bonus Step!**

Although it was not taught in Intermediate Python, a useful skill for visualizing different data points is to use a different marker. You can learn more about them via the Matplotlib documentation or via our course Introduction to Data Visualization with Matplotlib. Thus, as a bonus step, try to differentiate guest appearances not just with size, but also with a star!

All other attributes still apply (data on the axes, color scheme, sizes for guest appearances, title, and axis labels).


## Project 2: What and Where are the World's Oldest Business
### Project Description
An important part of business is planning for the future and ensuring that the business survives changing market conditions. Some businesses do this remarkably well and last for hundreds of years. In this project, you'll explore data from BusinessFinancing.co.uk on the world's oldest businesses: when were they founded, and which industries do they belong to?

Like many business problems, the data we'll explore is contained in several different datasets. In order to understand the world's oldest businesses, we will first need to use joining techniques to merge our data. From there, we can use manipulation tools such as grouping and filtering to answer questions about these historic businesses.

### Project Tasks
1. The oldest businesses in the world
2. The oldest businesses in North America
3. The oldest business on each continent
4. Unknown oldest businesses
5. Adding new oldest business data
6. The oldest industries
7. Restarurant representation
8. Categries and continents



## Project 3: The Android App Market on Google Play
### Project Description
Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this project, you will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. You'll look for insights in the data to devise strategies to drive growth and retention. The data for this project was scraped from the Google Play website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:

* `apps.csv`: contains all the details of the apps on Google Play. These are the features that describe an app.
* `user_reviews.csv`: contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed, passed through a sentiment analyzer engine and tagged with its sentiment score.

### Project Tasks 1
1. Google Play Store apps and reviews
2. Data cleaning
3. Correcting data types
4. Exploring app categories
5. Distribution of app ratings
6. Size and price of an app
7. Relation between app ategory and app price
8. Filter out "junk" apps
9. Popularity of paid apps vs free apps
10. Sentiment analysis of user reviews

### Project Tasks 2
You work as a Data Analyst for a finance company which is closely eyeing the Android market before it launches its new app into Google Play. You have been asked to present an analysis of Google Play apps so that the team gets a comprehensive overview of different categories of apps, their ratings, and other metrics.

This will require you to use your data manipulation and data analysis skills.

Your three questions are as follows:

1. Read the `apps.csv` file and clean the `Installs` column to convert it into integer data type. Save your answer as a DataFrame `apps`. Going forward, you will do all your analysis on the `apps` DataFrame.

2. Find the number of apps in each category, the average price, and the average rating. Save your answer as a DataFrame `app_category_info`. Your should rename the four columns as: `Category`, `Number of apps`, `Average price`, `Average rating`.

3. Find the top 10 free `FINANCE` apps having the highest average sentiment score. Save your answer as a DataFrame `top_10_user_feedback`. Your answer should have exactly 10 rows and two columns named: `App` and `Sentiment Score`, where the average `Sentiment Score` is sorted from highest to lowest.


## Project 4: A Visual History of Nobel Prize Winners
### Project Description
The Nobel Prize is perhaps the world's most well known scientific award. Every year it is given to scientists and scholars in chemistry, literature, physics, medicine, economics, and peace. The first Nobel Prize was handed out in 1901, and at that time the prize was Eurocentric and male-focused, but nowadays it's not biased in any way. Surely, right?

Well, let's find out! What characteristics do the prize winners have? Which country gets it most often? And has anybody gotten it twice? It's up to you to figure this out.

The dataset used in this project is from The Nobel Foundation on Kaggle.

### Project Tasks
1. The most Nobel of Prizes
2. So, who gets the Nobel Prize?
3. USA dominance
4. USA dominance, visualized
5. What is the gender of a typical Nobel Prize winner?
6. The first woman to win the Nobel Prize
7. Repeat laureates
8. How old are you when you get the prize?
9. Age differences between prize categories
10. 




