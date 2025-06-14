# BURNOUT_A_MotoGP_Datathon
A high-octane 12-hour datathon 🏍️ that brings together the thrill of MotoGP racing and the power of data analytics! Compete on Kaggle, dive into complex MotoGP datasets, and use machine learning 🧠 to predict race outcomes and uncover game-changing insights
<br>
# Burnout 2025: MotoGP Data Analytics Challenge 🏁
IEEE Computer Society MUJ presents Burnout 2025! 🌟 Step into the fast-paced world of MotoGP racing and analyse rider performance, lap times, and race strategies across multiple seasons. With a dataset packed with racing stats, this competition provides a comprehensive look at the sport’s dynamics, challenging you to push the boundaries of data science in motorsports.
<br>
# Team Details
Team Name: Azertronz
Members: Jayam V & Nishok A
<br>
# DataSet Information
## Columns
Unique ID: A unique identifier for each row in the dataset.
Rider_ID: Unique identifier assigned to each rider.
category_x: The racing category (e.g., MotoGP, Moto2).
Circuit_Length_km: Total length of the race circuit in kilometers.
Laps: Number of laps in the race.
Grid_Position: Starting position of the rider on the grid.
Avg_Speed_kmh: Average speed of the rider during the race (in km/h).
Track_Condition: Surface condition of the track (e.g., dry, wet).
Humidity_%: Humidity level during the session, in percentage.
Tire_Compound_Front: Type of tire compound used on the front tire.
Tire_Compound_Rear: Type of tire compound used on the rear tire.
Penalty: Penalties incurred by the rider during the race.
Championship_Points: Total points accumulated in the championship so far.
Championship_Position: Current rank in the championship standings.
Session: Type of session (Race, Qualifying, Practice, etc.).
Year_x: Year in which the session took place.
Sequence: Order or sequence of the entry within a session or race.
Rider: A unique identifier assigned to each rider.
Team: A unique identifier assigned to each team.
Bike: A unique identifier assigned to each bike.
Position: Final finishing position in the race.
(-1 = DNF (Did Not Finish), -2 = DNS (Did Not Start), -3 = DSQ (Disqualified), -4 = DNQ (Did Not Qualify / Technical issue))
Points: Points awarded for the race based on finishing position.
Shortname: Abbreviated or nickname version of the country.
Circuit_name: Full name of the circuit where the race took place.
Rider_name: Full name of the rider.
Team_name: Full name of the team.
Bike_name: Model of the bike.
Lap_Time_Seconds: Average time per lap in seconds (Target Variable).
Corners_per_Lap: Number of corners in one lap of the circuit.
Tire_Degradation_Factor_per_Lap: Average tire wear rate per lap.
Pit_Stop_Duration_Seconds: Time spent during pit stops, in seconds.
Ambient_Temperature_Celsius: Air temperature during the session.
Track_Temperature_Celsius: Track surface temperature during the session.
Weather: Weather condition (e.g., sunny, rainy).
Track: Track temperature.
Air: Air temperature.
Ground: Ground or surface temperature of the track.
Starts: Total number of race starts in the rider's career.
Finishes: Total number of races the rider finished.
With_points: Number of races where the rider scored points.
Podiums: Number of times the rider finished in the top 3.
Wins: Number of race victories.
Min_year: First year the rider competed.
Max_year: Most recent year the rider was active.
Years_active: Total number of active racing years.
<br>
## 📁 Files Included:
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
val.csv - to check accuracy on unknown data
<br>
# Evaluation Metric
Root Mean Squared Error (RMSE) is a commonly used evaluation metric for regression problems in Kaggle competitions. It measures the average magnitude of the errors between the predicted and actual values, providing an indication of the model's accuracy.
<br>
Competition link: https://www.kaggle.com/c/burnout-datathon-ieeecsmuj
