# EDA-Youtube
This project utilizes the YouTube Data API to scrape data from YouTube by generating an API key and analyze the popularity of music artists based on likes, views, and other statistics using python and visualizing them using matplotlib. The goal is to identify the most popular music artists and visualize the findings.

The project involves the following steps:

# Collecting Data:

A list of music artist channel names is defined.
The channel names and corresponding playlist IDs are extracted from the channel data.
Fetching Video Details:
For each music artist, the video IDs of their playlist are obtained using the YouTube Data API.
The video details, including title, published date, views, likes, dislikes, and comments, are fetched using the YouTube Data API.

# Analyzing and Visualizing Data:

The video details are processed and stored in a suitable data structure.
The video data is grouped by music artist and sorted based on likes.
The top 5 videos with the highest number of likes for each music artist are selected.
Bar graphs are created using the Matplot library to visualize the top videos by likes for each music artist.

# Saving Data:

The video details for each music artist are saved in separate CSV files.
Each CSV file contains the columns 'Title', 'Published_date', 'Views', 'Likes', 'Dislikes', and 'Comments'.
The CSV files are named based on the music artist's channel name followed by "_video_details.csv".

# The project provides valuable insights into the popularity of music artists based on YouTube video data. It allows for comparisons between different artists and enables the visualization of top videos based on different statistics. The data can be further analyzed or used for reporting purposes.
