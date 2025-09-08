<h1>Project Description</h1>

This project was assigned by the company with the main objective of calculating player loyalty points, identifying the top loyal players, distributing bonus money fairly, and providing meaningful insights for stakeholders. The task combines data processing using Python and interactive reporting using Power BI, ensuring both technical accuracy and business usability.

<h1>Objective<h1>

 The project focuses on creating a Loyalty Point System that evaluates player engagement and spending behavior. The company wants to:

 Calculate loyalty points for all players.

 Identify the top 50 most loyal players.

 Allocate bonus money fairly based on these points.

 Provide dashboards and insights that can help management take better decisions regarding customer engagement, retention, and promotions.

<h1>Dataset<h1>

 Three datasets were provided for this project:

 Gameplay Dataset – Contains details like User Id, Games Played, Date & Time. This dataset highlights player activity and frequency of participation.

 Deposit Dataset – Contains User Id and Deposit Amount. It represents how much money each player has invested in the platform.

 Withdrawal Dataset – Contains User Id and Withdrawal Amount. It reflects how much money players are taking out of the platform.

 The datasets were first cleaned using Python: unnecessary values were dropped, missing data was filled, and columns were renamed for better readability. The Date   & Time column was converted into a proper datetime format, and from it, day, month, and time slots were extracted. These transformations helped in generating       deeper insights like peak engagement periods and inactive slots.

<h1>Python Source File<h1>

 The Python file (User-Gameplay-and-Revenue-Tracker Using Python.ipynb) was used for the following tasks:

 Data Cleaning: Handled missing values, dropped irrelevant rows/columns, and standardized column names.

 Feature Engineering: Converted datetime columns and extracted useful time-based features.

 Loyalty Point Calculation: A formula was applied that combined gameplay activity and deposits/withdrawals to assign loyalty points to each user.

 Analysis Preparation: Created new tables such as the loyalty point table and summarized data for visualization.

 Fairness Check: Tested if the loyalty point formula was fair by comparing players who play frequently vs. players who spend more.

 Python ensured that the data was properly structured and calculated before feeding into visualization tools.

<h1>Power BI File<h1>

 The Power BI file (User Gameplay and Revenue Tracker Dashboard.pbix) was used to present interactive insights from the processed dataset. The dashboards included:

 Distribution of Loyalty Points: Showed that most players earned very low points, while a few top players dominated the pool.

 Top 10 and Top 50 Players: Highlighted high-value customers who deserve special attention for retention and rewards.

 Games Played vs. Loyalty Points (Scatter Plot): Demonstrated a positive correlation between engagement and loyalty, though other factors also played a role.

 Deposit Analysis: Showed that most players deposited small amounts, but a few high-value depositors contributed significantly.

 Engagement Patterns by Time Slots: Identified periods of peak and zero activity.

 The Power BI dashboard turned the backend calculations into clear, business-friendly visuals that help management quickly spot trends and make data-driven decisions.


 <h1>Results<h1>

  The analysis revealed several important insights:

  A small group of top players contributed a significant share of loyalty points and revenue, highlighting the importance of focusing on VIP players.

  Most users earned very few points, showing a skewed distribution and confirming that a majority are casual players.

  Engagement patterns were stable across time slots, though certain slots (like 16-Oct-S2) showed peak performance.

  Deposit and loyalty behaviors were similar: most contributed small amounts, while a small number dominated totals.

<h1>Conclusion<h1>

 This project successfully integrated Python for data processing and Power BI for visualization to build a fair and effective loyalty points system. The results showed that most users        contribute little, while a small number of high-value customers drive most of the revenue and loyalty points. By recognizing and rewarding these loyal customers, the company can improve     retention and strengthen its business growth.
