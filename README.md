# REP_COUNTER
REP counter for Knee Bend exercise

The model will calculate the angle between the user’s hip, knee and ankle, and will assume that the user’s bending their knee if the angle is less than 120 degree and considered as a count and marked as “UP” stage. Once the Stage is “UP”, timer will start. When the user stretches their leg straight, the angle will be greater than 160 degree and it will be considered as “DOWN” stage. Now, the algorithm will calculate the holding time between ‘UP’ and ‘DOWN’ stages. If the holding time is lesser than 8 seconds, feedback will appear on the screen as ‘Keep your Knee bent’.
