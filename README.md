# dsa210_project

## Description
DSA210 - Introduction to Data Science Term Project

- This project explores patterns and trends in my Youtube habits by analyzing my viewing history data.
- You can find the presentation here: https://drive.google.com/file/d/1gtUBOO90QbqBV2n4ebWwedO2aFADQMng/view?usp=sharing
- This README file contains some extra information I didn't put in the presentation. Please see the presentation.

## Motivation
A significant part of our lives are now lived through our phones, which is why I wanted to analyze my online behaviours and trends. I decided to choose an app that I use frequently whose data will tell a lot about myself, Youtube,
whose data offers a deep understanding about my habits and preferences.

I spend a lot of hours consuming content on Youtube, whether it be educational, sportive or entertaining. With this project, I aim to uncover some patterns behind the videos I watch, such as:

- What type of content do I watch
- Percentage of likes over videos viewed 
- Is there any preffered/favored content creators
- Daily/Weekly watching habits
- My subscriptions
- Search history

## Dataset
The dataset is easily obtained from Google Takeout with my Youtube Account.

The dataset includes:

- Viewing History
- Search History
- Subscriptions
- Comments and Live Chats
- Playlists

## Data Analysis
1. Export and Prepare Data
   - Export data through Google Takeout
   - Clean, tweak data to make it structured and ready
2. Visualization and Explarotary Data Analysis (EDA)
   - Visualize the data with charts to show patterns, such as viewed content type or time of day habits
   - Identify patterns in viewing history
   - Analyze the aspects mentioned in the motivation part
3. Hypothesis Testing
   - Hypothesis: The 5 most watched channels make up more than 10% of the total videos watched.
   - Test the hypothesis.
4. ML Model
   - Create a ml model to predict the total number of videos Im going to watch on a given day.

## Findings
- Seeing which channels made it to my top 15
- Seeing in which part of the day I was more active
- Seeing in which day I was more active
- Watching a lot of videos in the year 2022
- My own channel is in my top 15 watched channels :D
- Finding out that I always change things that I watch and dont stick to one channel.
- My habits and interest change quickly and its correlation with my viewing habits.
## Limitations and Future Work
- The biggest problem with this project was the fact that the total hours I watched a video wasn't given. The data was about me clicking a video. This is a major issue because it would still be showing the video in the data even if I clicked off from it after one second. This is also the reason why some channels are higher up in my top fifteen, because of constantly clicking on and off videos.
- If there was a way to track the total hours watched, a more thorough analysis could be done to determine stuff like
  1. Average watch time of a video
  2. Average percentage of videos watched
  3. Hours spent on categories
  4. Hours spent on top 10 channels.
- Lets say we have channel A and channel B.Suppose I watched 10 channel A videos where each video was 1 hour long and 20 B videos where each video was 30 seconds long. Currently because of the data set's structure, my top watched channel is the B channel, however it is obvious that I sank more time into channel A.
