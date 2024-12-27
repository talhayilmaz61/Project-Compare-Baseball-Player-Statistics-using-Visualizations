# Project-Compare-Baseball-Player-Statistics-using-Visualizations
"Judge vs. Stanton: Power Hitters in MLB" Explore Statcast data to compare MLB giants Aaron Judge and Giancarlo Stanton. Both players dominated the league in home runs in 2017, hitting 59 and 52, respectively. This project visualizes their performances and highlights their unique strengths as two of baseball's most powerful hitters.

Tasks:
How many of each event did Judge and Stanton have in 2017?

Save your answer as two Pandas Series: judge_events_2017 and stanton_events_2017.
The events should be the index, and the event counts should be in descending order.
Which player hit home runs slightly lower and harder?

Visualize the launch_speed versus launch_angle for each players' home runs with one plot for each player. Save the plots under fig1 and ax1.
Save either "Stanton" or "Judge" to a variable named player_hr.
Compare the pitch velocity, or release_speed, for both players using plots. Which player hit their home runs off of faster pitches (has the highest median)?

Save either "Stanton" or "Judge" to a variable named player_fast.
Construct a 2D histogram for each player that visualizes the home run strike zones, ignoring zones 11, 12, 13, and 14 for simplicity.

Create a new filtered DataFrame for each player called judge_strike_hr and stanton_strike_hr.
Use the custom functions provided to assign coordinates to the data; save these as new columns zone_x and zone_y in the new DataFrames.

**The Data**

There are two CSV files, `judge.csv` and `stanton.csv`, both of which contain Statcast data for 2015-2017. Each row represents one pitch thrown to a batter. 

**Custom Functions**

Two functions have also been provided for you to visualize home rome zones
- `assign_x_coord`: Assigns an x-coordinate to Statcast's strike zone numbers.
- `assign_y_coord`: Assigns a y-coordinate to Statcast's strike zone numbers.
