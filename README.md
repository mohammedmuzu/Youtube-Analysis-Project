# Youtube-Analysis-Project

### Summary of the YouTube Video Analysis Project

This project focuses on analyzing YouTube video data to identify trends and insights related to video performance, such as views, likes, comments, and publishing dates. The analysis was performed on a dataset containing various metrics about the videos, using the YouTube Data API to retrieve detailed information.

#### **Key Objectives**
- Fetch data on YouTube videos, including views, likes, and comments.
- Analyze the top-performing videos based on view count.
- Visualize the data to gain insights into video popularity and audience engagement.

#### **Steps Involved**

1. **Data Collection**:
   - YouTube video details were retrieved using the YouTube Data API.
   - Data fields included video `Title`, `Published_Date`, `Views`, `Likes`, `Comments`, and additional metadata like `Duration` and `Definition`.

2. **Data Cleaning**:
   - The raw data retrieved from the API was processed to handle missing values, particularly for videos that might not have comments enabled.
   - Data types were converted, such as converting `Views`, `Likes`, and `Comments` to numeric types, and transforming `Published_Date` into a date format.

3. **Data Analysis**:
   - The videos were sorted based on view count to identify the top 10 most viewed videos.
   - Metrics such as `Likes` and `Comments` were also analyzed to understand engagement levels for these top-performing videos.

4. **Visualization**:
   - A bar chart was created to display the top 10 videos by views, providing a visual overview of the most popular content.
   - The chart showcased video titles along the y-axis and view counts on the x-axis, making it easy to compare the performance of different videos.

#### **Findings**
- The top 10 most viewed videos were identified, with view counts ranging from millions to hundreds of millions.
- A visual representation of the most popular videos was created, allowing for easy comparison of which content performed best in terms of views.

#### **Challenges**
- Handled cases where some videos had missing comment counts or disabled comments.
- Adjusted font settings to ensure proper rendering of video titles containing special characters or Unicode glyphs.

#### **Conclusion**
The project successfully analyzed a set of YouTube video data, identifying the most popular content by views and providing visual insights into video performance. This analysis can guide content creators and marketers in understanding which videos resonate most with their audience and what types of engagement patterns are associated with popular content.
