# CS210ProjectMel

Presentation link: https://prezi.com/view/sieNSk4zK6GDySLo2o4d/

Research Questions: Is there a significant relationship between the time of day and the type of content consumed on video platforms?

Hypothesis: 
Null Hypothesis (H₀):
There is no relationship between the time of day and the type of content category watched. The two variables are independent.

Alternative Hypothesis (H₁):
There is a significant relationship between the time of day and the type of content category watched. The choice of content depends on the time of day.

Analyzing YouTube Consumption: The project investigates the relationship between the time of day and the type of video content consumed on a platform. The goal is to determine whether viewing preferences for different content categories (e.g., Music, TV/Drama, Education) vary depending on the time of day (Morning, Afternoon, Evening, Late Night).

Motivation: The project aims to explore whether the time-of-day affects the type of content watched, such as Music, TV/Drama, or Educational videos. Understanding this relationship can help improve personalized content recommendations on streaming platforms by suggesting videos that users are more likely to watch at specific times. 

Data Source: Download YouTube History, Use Google Takeout to export YouTube watch history:

1-Visit Google Takeout.

2-Select "YouTube and YouTube Music."

3-Choose "History" and download the data as a JSON file.

What's in the Data?

1-The file will contain information like:

2-Video titles.

3-URLs.

4-Watch timestamps.

Methadology:
1. Data Collection: Video watch history dataset.
2. Data Cleaning: Filtering relevant columns (time-of-day and content category).
3. Analysis: Using contingency tables, bar charts, and heatmaps to explore correlations.
4. Statistical Test: Chi-Square Test for Independence to determine significance.

Analysis Steps:
1. Data Preprocessing:
   
-Parse the JSON file and convert it into a structured format for example a DataFrame in Python.

-Clean the data by removing duplicates or irrelevant entries for example autoplay videos.

2. EDA (Exploratory Data Analysis):
   
-Watching patterns:

Find the time of day or days in the week that you watch most videos.

Analyze the amount of time spent on YouTube in a day, a week, or a month.

-Content preferences:

Create the categorization of the content into title-based, channel-based, or description-based, such as Educational, Entertainment, and Music.

Visualization via pie chart or bar chart.

-Engagement trend:

Find channels or genres that have the highest repeat viewership rate.

3. Visualization: 
Libraries like Matplotlib or Plotly could be used to display the following:

heatmap: the intensity of viewing during the day/week.

line charts: to show trends over time. 

word clouds of video titles to bring out recurring themes. 

Tools and Technologies:

Programming Languages: Python

Possible Libraries that will be used:

-pandas and numpy for data manipulation/processing

-matplotlib and/or seaborn for visualization

(-scikit-learn for clustering and/or predictive modeling)

Documentation: README within the GitHub repository.






