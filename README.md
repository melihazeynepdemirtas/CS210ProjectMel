# CS210ProjectMel

Analyzing YouTube Consumption: This project covers the history of individual YouTube views to find patterns and preferences and investigate possible reasons for how these patterns affect daily routines.

Motivation: Gain some insight into the time spent on YouTube, the type of content viewed, and how that can relate to your productivity and mood.
From the insights gained on views, adjust screen time or your interests. 

Data Source: Download YouTube History, Use Google Takeout to export YouTube watch history:

1-Visit Google Takeout.

2-Select "YouTube and YouTube Music."

3-Choose "History" and download the data as a JSON file.

What's in the Data?

1-The file will contain information like:

2-Video titles.

3-URLs.

4-Watch timestamps.

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

-scikit-learn for clustering and/or predictive modeling

Documentation: README within the GitHub repository.






