# YouTube-Channels-Data-Analysis
# Introduction:
This project explores a dataset containing information about YouTube channels, sourced from Kaggle: 

**Link to dataset: **https://www.kaggle.com/datasets/rahuldogra/top5000youtubechannels?select=top-5000-youtube-channels.csv.  

The dataset is on the top 5000 YouTube channel dataset.
We aim to analyze key channel metrics and identify potential relationships between them.

# Data Acquisition and Libraries:
The dataset, "top-5000-youtube-channels.csv," was downloaded from Kaggle website. 
Python libraries pandas (pd) and seaborn (sns) were used for data manipulation and visualization.
# Data Description:
The dataset consists of 5,000 rows (channels) and 6 columns containing the following information:

•	Rank: The ranking position of the channel (e.g., 1st, 2nd, etc.).

•	Grade: A categorical variable, possibly representing a rating or classification of the channel.

•	Channel name: The name of the YouTube channel.

•	Video Uploads: The number of videos uploaded by the channel.

•	Subscribers: The number of subscribers to the channel.

•	Video views: The total number of views across all videos of the channel.

# Data Cleaning:
Descriptive statistics were used to examine the data distribution. We observed:

•	All columns have 5,000 non-null values, indicating no missing data.

•	Descriptive statistics for "Rank" and "Grade" are not particularly informative due to their categorical nature.

•	"Video views" exhibits a significant standard deviation compared to the mean, suggesting a 
skewed distribution with potentially a few channels having a very high number of views.

•	The remaining columns ("Video Uploads" and "Subscribers") likely also have skewed distributions as they deal with counts.

# Exploratory Data Analysis		
# 1.	Correlation	
![image](https://github.com/user-attachments/assets/58e9974a-512a-4ccf-8216-f9b9de71ce70)


**Interpreting the Results:**
These correlations provide valuable insights into the YouTube channel ecosystem:

•**	Subscriber Growth:** To increase subscribers, channels should focus on producing consistent, high-quality content.

•**	Viewership: **Increasing video uploads and promoting existing videos can lead to more views.

**•	Channel Ranking:** High-quality content and consistent uploads can improve a channel's ranking.

# 2.	Analyzing the Relationship Between Grade and Average Views

![image](https://github.com/user-attachments/assets/eb055400-1b8c-4d91-94fe-6aad46185d8b)

The bar plot visualizes the relationship between the "Grade" of a YouTube channel and its average views.

It appears that Grade 4 has the highest average number of views among the displayed grades.
However, it's important to note that the error bars indicate the variability in the data. 

# 3.	Analyzing the Relationship Between Grade and Video Uploads

![image](https://github.com/user-attachments/assets/dd1c4de4-ec28-462a-98b1-8728aec68e1f)

Is there a relationship between the grade of a YouTube channel and the number of videos it uploads?"

The answer, based on the visualization, is yes. Higher-graded channels tend to upload more videos.

# 4.	Analyzing the Relationship Between Grade and Subscribers
The plot below addresses the question: "How does the grade of a YouTube channel impact its subscriber count?"

Grade as a Strong Indicator of Popularity: Higher-graded channels tend to have significantly more subscribers. 
This suggests that the grading system effectively categorizes channels based on their popularity and engagement.

![image](https://github.com/user-attachments/assets/0e725538-a8ac-47f8-a763-6ae85ce909e3)

Channels with higher grades likely produce high-quality content, consistent uploads, and effective marketing strategies, which contribute to increased subscriber growth.
# Recommendations
Based on the analysis of the YouTube channel dataset, we can provide the following recommendations:

**•	Quality Over Quantity:** While a higher number of videos can contribute to increased viewership, 
focusing on producing high-quality content that resonates with the target audience is crucial.

**•	Consistent Uploading Schedule**: Maintaining a consistent upload schedule helps to build a loyal audience and improve discoverability.

**•	Keyword Optimization:** Utilize relevant keywords in titles, descriptions, and tags to improve search engine optimization (SEO).

**•	Social Media Promotion:** Share videos on social media platforms to reach a wider audience.

**•	Collaborations: **Collaborate with other YouTubers to cross-promote content and reach new audiences.

**•	Paid Advertising:** Consider using YouTube Ads to promote videos and reach a targeted audience.

**•	Utilize Analytics:** Use YouTube Analytics to track key metrics like watch time, audience retention, and demographics.

**•	A/B Testing:** Experiment with different content formats, titles, and thumbnails to optimize performance.

# Conclusion
The analysis of the YouTube channel dataset has provided valuable insights into the factors that contribute to channel growth and success. 
By understanding the relationship between variables like grade, video uploads, subscribers, and views, we can identify key strategies for optimizing channel performance.
Future research could delve deeper into the impact of specific content formats, audience engagement metrics, and emerging trends in the YouTube ecosystem. 
By leveraging data-driven insights and continuous experimentation, YouTube channels can improve their visibility, attract more subscribers, and achieve sustained growth.



