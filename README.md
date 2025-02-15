Cricket Players Data Cleaning & Visualization with MMD! 🏏

I found a dataset of cricket players, but it was a total mess—tons of irrelevant and messy data. ☹️
So, I thought, why not clean it up and create some cool visualizations? 🥰
With Pandas, I cleaned the dataset, and with Matplotlib, I visualized the insights. 📈

Let’s dive in and see what happened! 😎

🛠️ Step 1: Data Cleaning 

✅ Loading the Dataset
I read the player.csv file and set player_id as the index.

✅ Dropping Unnecessary Columns
Columns like born and height weren’t useful, so I removed them.

✅ Removing Duplicates & Invalid Data

Deleted duplicate records to keep only one entry per player. Dropped missing or incomplete data for better accuracy. 

✅ Renaming Columns for Better Readability

names → Full Name bat_type → Bat Hand bowl_type → Bowl Hand matches → Matches Played country → Country 

Now, the dataset is much cleaner and more readable! 🚀

🎯 Step 2: Fixing Inconsistent Values 

📌 Extracting Bowling Speed

The Bowl Hand column contained both the hand type and speed. I separated them into two distinct columns. Replaced invalid values (Data) with NaN. 

📌 Fixing Batting Hand (Bat Hand)

Some values had extra descriptions (e.g., Slow left-arm orthodox), so I simplified them. Removed incorrect values like 0, slow, and Legbreak. 

📌 Handling Invalid Entries

Removed or corrected misleading values in Bowl Hand. 

Now, the dataset is clean and ready for analysis! 😍

📉 Step 3: Data Visualization 

Using Matplotlib, I created several eye-catching charts:

📌 Pie Chart – Player Distribution by Country

Displays the number of players from each country. Shows percentages for better insights. 

📌 Bar Chart – Matches Played by Batting Hand

Compares left-handed and right-handed players. Used orange and red for better contrast. 

📌 Bar Chart – Matches Played by Bowling Hand

Similar to the previous one but for bowlers. Used blue and green for clarity. 

📌 Scatter Plot – Bowling Speed vs. Matches Played

Answers the question: Do faster bowlers play more matches? 

📌 Histogram – Bowling Speed Distribution

Shows how bowling speeds are distributed among players. Used a purple theme with a white border for better readability. 

📌 Stacked Line Chart – Player Distribution by Country & Bowling Hand

Visualizes the number of players per country and their bowling type. Used white and yellow for a high-contrast display. ✅ Summary 

The raw dataset was a mess—extra columns, missing values, incorrect entries, and more. 😵

After cleaning and refining the data, I transformed it into a well-structured and reliable dataset. 🥰
Then, through visualization, I uncovered interesting patterns, such as player distribution, the impact of bowling speed on matches played, and many other cool insights. 😎

This project turned raw data into valuable insights—what an adventure! 🔥

