# Tableau_Game_Analytics_Dashboard-_User_Engagement_and_Gameplay_Insights

You can view the final project [here](https://public.tableau.com/app/profile/julia.macha7529/viz/GameAnalyticsDashboardUserEngagementandGameplayInsights/GameAnalyticsDashboardUserEngagementandGameplayInsights).

# Game Analytics Dashboard: User Engagement and Gameplay Insights

This Tableau project provides an in-depth analysis of user engagement and gameplay activities. The steps below outline the creation of the dashboard, detailing each component and its purpose.

## Steps Undertaken

### Sheet 1: MUser and Battle Pass Analysis
The first sheet was created to display two key metrics on a monthly basis:
1. **Total Number of Game Users**: This metric shows the overall count of users engaging with the game each month.
2. **Percentage of Users Engaged in 'Battle Pass' Activities**: This metric calculates the percentage of total users who participated in any 'Battle pass' activities. The `game_activity_name` field was used to identify relevant activities.

### Sheet 2: Average Player Gameplay Time
The second sheet visualizes the average time each player spends in the game for each month:
- **Average Time Spent in Game**: This metric calculates and displays the average hours and minutes spent in the game per user.
- **Label**: A text label was added to show the average time in the format "HH:MM". The format ensures that the minutes always have two digits (e.g., 00:02, 21:07, 05:53).

### Sheet 3: Heatmap: Gameplay Time by Age Group and Quarter
The third sheet presents a heat map to show the average time spent in the game based on:
- **Age Group**: Users were divided into 5-year age intervals (e.g., "10-14", "15-19", ..., "80-84").
- **Activity Date Quarter**: The data was segmented by quarters of the activity date.

### Dashboard Integration - Game Analytics Dashboard: User Engagement and Gameplay Insights
All three sheets were then integrated into a single dashboard. To enhance the user experience, interactive filters were added:
- **Activity Date Filter**: Allows users to filter data by specific activity dates.
- **Age Group Filter**: Enables filtering by different age groups.
- **Game Name Filter**: Includes a filter for the game names as listed in `game_activity_name`.
- **Device Language Filter**: Adds a filter for the user’s device language.

## Final Product
The resulting Game Analytics Dashboard offers a comprehensive view of user engagement and gameplay insights. This dashboard allows for detailed analysis of user behavior and game performance over time, helping to identify trends, understand user demographics, and optimize game features to enhance user experience.

