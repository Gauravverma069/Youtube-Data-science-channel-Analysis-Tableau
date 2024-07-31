# Data Science Channels on YouTube - Tableau Dashboard

## Overview

This project visualizes various statistics of YouTube channels focused on Data Science. The Tableau dashboard includes multiple sheets that provide insights into the number of videos, viewership trends, and engagement metrics for these channels. The aim is to help users understand the performance and popularity of different Data Science channels on YouTube.

### Dashboard Page1
![image](https://github.com/user-attachments/assets/1c5bacac-8e54-4892-bf52-fa7a064c8291)

### Dashboard Page2
![image](https://github.com/user-attachments/assets/b6b09e7a-5188-48d2-a3d2-c9d11f24d488)

## Dashboard Sheets

The dashboard consists of the following sheets:

1. **Number of Videos per Channel**
   - This sheet displays the total number of videos uploaded by each channel.

2. **Yearwise Viewership**
   - This sheet shows the viewership trends over the years, highlighting how views have changed annually.

3. **Average Likes per Channel**
   - This sheet presents the average number of likes received per channel, providing an idea of audience engagement.

4. **Average Views per Channel**
   - This sheet illustrates the average number of views per channel, indicating the reach of the channels.

5. **Average Comments per Channel**
   - This sheet shows the average number of comments per channel, reflecting the interaction level with the audience.

6. **Average Views vs. Average Likes**
   - This sheet compares the average views to the average likes per channel, helping to understand the correlation between these metrics.

7. **Average Views vs. Average Comments**
   - This sheet compares the average views to the average comments per channel, providing insights into viewer engagement.

8. **Average Comments per Channel**
   - This sheet aggregates the average number of comments per channel, offering a perspective on audience feedback.

## Data Source

The data used for this dashboard includes the following columns:
- `Channel_Name`: Name of the YouTube channel
- `Title`: Title of the video
- `Published_date`: Date the video was published
- `Views`: Number of views the video received
- `Like_count`: Number of likes the video received
- `Comment_Count`: Number of comments on the video

## Usage

To explore the dashboard:

1. Open Tableau Desktop or Tableau Public.
2. Load the provided `.twb` file.
3. Navigate through the different sheets to view various insights and visualizations.

## Key Insights

- WsCube Tech is the most active Data Science channels based on the number of videos with over 5000 videos.
- Viewers in Data science increase from 2017 and peaked at 2021, with more engagement during COVID.
- Learn Python - Full Course for Beginners have the highest views with over 44 Millions.
- Andrej Karpathy has the hightest avg Like, avg view, avg comment approx 2x that of 2nd channel viewership.
- In India viewership started to rise after Covid with WsCube Tech videos being in 7 out of top 10 vieweship with, Rishabh channel being the most engaging channel.
- Tina Huang has the highest avg like per views with 4.9%, similarly in India Rishabh channel is has the highest avg. like per view with 3.8%.
- views correlation between likes, and comments is linear.

## Future Work

- Incorporate more channels and data points to enhance the comprehensiveness of the analysis.
- Add interactive filters to allow users to customize their view of the data.
- Update the dashboard periodically to reflect the latest data and trends.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
