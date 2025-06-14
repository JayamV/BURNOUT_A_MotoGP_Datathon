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
*Unique ID:* A unique identifier for each row in the dataset. <br>
Rider_ID: Unique identifier assigned to each rider. <br>
category_x: The racing category (e.g., MotoGP, Moto2). <br>
Circuit_Length_km: Total length of the race circuit in kilometers. <br>
Laps: Number of laps in the race. <br>
Grid_Position: Starting position of the rider on the grid. <br>
Avg_Speed_kmh: Average speed of the rider during the race (in km/h). <br>
Track_Condition: Surface condition of the track (e.g., dry, wet). <br>
Humidity_%: Humidity level during the session, in percentage. <br>
Tire_Compound_Front: Type of tire compound used on the front tire. <br>
Tire_Compound_Rear: Type of tire compound used on the rear tire. <br>
Penalty: Penalties incurred by the rider during the race. <br>
Championship_Points: Total points accumulated in the championship so far. <br>
Championship_Position: Current rank in the championship standings. <br>
Session: Type of session (Race, Qualifying, Practice, etc.). <br>
Year_x: Year in which the session took place. <br>
Sequence: Order or sequence of the entry within a session or race. <br>
Rider: A unique identifier assigned to each rider. <br>
Team: A unique identifier assigned to each team. <br>
Bike: A unique identifier assigned to each bike. <br>
Position: Final finishing position in the race. <br>
(-1 = DNF (Did Not Finish), -2 = DNS (Did Not Start), -3 = DSQ (Disqualified), -4 = DNQ (Did Not Qualify / Technical issue)) <br>
Points: Points awarded for the race based on finishing position.<br>
Shortname: Abbreviated or nickname version of the country. <br>
Circuit_name: Full name of the circuit where the race took place. <br>
Rider_name: Full name of the rider. <br>
Team_name: Full name of the team. <br>
Bike_name: Model of the bike. <br>
Lap_Time_Seconds: Average time per lap in seconds (Target Variable). <br>
Corners_per_Lap: Number of corners in one lap of the circuit. <br>
Tire_Degradation_Factor_per_Lap: Average tire wear rate per lap. <br>
Pit_Stop_Duration_Seconds: Time spent during pit stops, in seconds. <br>
Ambient_Temperature_Celsius: Air temperature during the session. <br>
Track_Temperature_Celsius: Track surface temperature during the session. <br>
Weather: Weather condition (e.g., sunny, rainy). <br>
Track: Track temperature. <br>
Air: Air temperature. <br>
Ground: Ground or surface temperature of the track. <br>
Starts: Total number of race starts in the rider's career. <br>
Finishes: Total number of races the rider finished. <br>
With_points: Number of races where the rider scored points. <br>
Podiums: Number of times the rider finished in the top 3. <br>
Wins: Number of race victories. <br>
Min_year: First year the rider competed. <br>
Max_year: Most recent year the rider was active. <br>
Years_active: Total number of active racing years. <br>
<br>
## 📁 Files Included:
train.csv - the training set <br>
test.csv - the test set <br>
sample_submission.csv - a sample submission file in the correct format <br>
val.csv - to check accuracy on unknown data <br>
<br>
# Evaluation Metric
Root Mean Squared Error (RMSE) is a commonly used evaluation metric for regression problems in Kaggle competitions. It measures the average magnitude of the errors between the predicted and actual values, providing an indication of the model's accuracy.
<br>
Competition link: https://www.kaggle.com/c/burnout-datathon-ieeecsmuj
