# Ola Cabs Social Media Sentiment and Engagement Analysis

## Project Overview

This project analyzes social media posts (tweets) related to Ola Cabs to understand customer sentiment, engagement, and identify complaints. The dataset includes post content, engagement metrics (likes, shares, comments), and user details such as mentions, hashtags, and media links. The project includes data cleaning, descriptive analysis, sentiment analysis, customer complaints extraction, and engagement analysis.

## Dataset Overview

The dataset contains the following fields:

- **Post Content**: The text of the post or tweet.
- **Datetime**: The date and time when the post was made.
- **Likes, Shares, Views**: Engagement metrics for the post.
- **Hashtags**: Any hashtags used in the post.
- **Media Links**: Links to any media attached to the post.
- **User Details**: Information about the user making the post.
- **Mentions and Comments**: Mentions of other users and user comments on the post.

## Tasks and Analysis

### 1. Data Cleaning and Preparation
- Cleaned the dataset by removing unwanted data, such as missing values and irrelevant information.
- Prepared the data for analysis by converting datetime to proper formats, handling missing engagement metrics, and extracting relevant columns.

### 2. Descriptive Analysis
- **Basic Statistics**: Calculated mean, median, and mode for engagement metrics like likes, shares, and views.
- **Top 5 Posts**: Identified the top 5 posts with the highest engagement based on the sum of likes, shares, and comments.
- **Media Attachments**: Counted the number of posts containing media attachments (e.g., images, videos).

### 3. Sentiment Analysis
- Performed sentiment analysis on the post content using **TextBlob** and **VADER** sentiment analysis libraries.
- Categorized posts into **Positive**, **Neutral**, or **Negative** sentiment.
- Calculated the percentage distribution of posts in each sentiment category.

### 4. Customer Complaints
- Extracted posts mentioning complaints about drivers, booking cancellations, and customer service issues.
- Categorized these posts based on the type of complaint (e.g., driver behavior, booking issues, customer service).
- Visualized the distribution of complaint categories using a bar chart.

### 5. Engagement Analysis
- **Correlation Analysis**: Analyzed the correlation between the number of followers and engagement metrics (likes, shares, comments).
- **Source Patterns**: Identified patterns in engagement based on the source of posts (Twitter, Instagram, etc.).

### 6. Recommendations
- Based on the findings, suggested actionable recommendations to improve Ola Cabs’ customer experience and social media engagement:
  1. Improve customer support and resolution times to address complaints.
  2. Leverage posts with media attachments to boost engagement.
  3. Focus on enhancing the behavior of drivers to reduce customer dissatisfaction.

## Technologies Used

- **Python**
- **Pandas**: For data manipulation and analysis.
- **Seaborn**: For data visualization.
- **TextBlob**: For sentiment analysis.
- **VADER**: For sentiment analysis.


