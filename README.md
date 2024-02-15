Spotify

Spotify is an audio streaming media service. In 2010, only 35 percent of internet users streamed music. Pandora and YouTube were the dominant players. By 2019, music streaming grew to 82 percent.
Our project will analyze Spotify’s underlying trends in the music industry from 2010 to 2019. The analysis will answer the following questions:
 
What is the average duration of songs based on genre? Is the difference between each average and the overall average statistically significant?

Are specific music keys favored? Has this changed over the 2010s? What does variation in the data look like by genre?

How much do acousticness, liveness, tempo, and valence vary between genres? How did they change by genre over the 2010 decade?

Does competition affect song popularity?

Is overall track popularity affected by the total number of track releases in the same month?

Our project is completed by a team of 4 members. After a brain storming session, we started with fitness and end up pursuing music. We faced challenges in obtaining an API-key and almost changed the project. But finally, with much perseverance we landed on a Spotify data set. We came up with interesting questions related to music and streaming industry. We collaborated, assigned the responsibilities, and met a few times to review the results and had open communication on slack.
Each member worked on 1 or 2 questions, providing analysis and  charts for better visualization. 
The team lead created the main file and each member created their individual branch. Each member uploaded their Jupyter notebook to the main branch. 
The team lead also created google documents for the presentation and the one page summary. This allowed each member to update the files. 

Our analysis aims to explore trends by genre within the ten years as well as aspects of music that may have changed over time by genre. This information could be useful to musicians, producers, and other stakeholders in the music industry. Some of the graphs explore whether the changes in the commodification and listening of music over this period as well as the growth of streaming service created playlists has affected trends in different musical qualities. It is clear that there is less variation in tempo and valence per genre in the later years, which could be due to musician's aims to get their music on curated playlists that may aim for specific tempos or valence levels.
   
Our project includes bar charts, boxplots, and line charts to illustrate different genre attributes. We also include a pie charts, a chi square test, and a chart of statistical significance.
Our line charts convey musical qualities over time, between 2010-2019, with one line for each genre per graph.
Our boxplots display the interquartile range and outliers for accousticness, tempo, valence, and liveness for each of the genres. A box plot was used to easily visualize/demonstrate that two keys were outliers of the data for the number of songs in each key.

Bar chart representing the mean duration by genre. The bar chart makes it easy to compare and quick see the genre with  longer or shorter duration.
The line chart represents number of songs and their associated duration. It made sense to break the duration into bins. The line chart is appropriate to show the continuous value of duration.
Perform a hypothesis test  on the mean duration by genre versus the overall mean duration. The Chi-Square revealed that there is a statistically significant variance between the mean durations.

Bar charts with a dashed red line to visualize the mean value were used to easily visualize:
1. Number of songs in each key for a given period of time, or
2. Percent of total songs in a specific key for a given genre

In order to generate these charts, we had to install pyplot for graphing charts, pandas as pd to use dataframes, scipy for plotting charts, linegress to get regression starts, and numpy. 

This project could be expanded by exploring more recent data using the spotify api or merging more datasets about these songs. It could also be expanded upon by assessing the playlists and the song make up of the playlists.

Resources:
https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs

Outputs:
https://docs.google.com/document/d/1K1r8oNNJdF2BwQsVvwXXthXA3jVeDRz77yu9jjv0qnk/edit?usp=sharing
https://docs.google.com/presentation/d/1i3mTu4yvklBcKaOf7oZISzM3c1ReNusiI3u2h50Fwmk/edit#slide=id.g2b808d09c4f_0_10

