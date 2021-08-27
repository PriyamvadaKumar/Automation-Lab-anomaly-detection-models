# Automation-Lab-anomaly-detection-models

Used isolation forest to detect anomalies in the location, motor current and gripper force of KX-2 laboratory robot arm 
and designed automated closed loop pipelines to take corrective actions and alert scientists/lab technicians 

# Methodolgy : Location, Motor Current and Gripper Force

-- Location,

Trained on 50 % of both expected location and 50% of actual location of normal data  - axis wise 

Tested on a remaining normal data and all of abnormal data (simulated degradation) 

Output : Label (normal/abnormal) & metrics for model performance 

--Current - Location,

Trained on 50% of actual location and 50 % of motor current of normal data- axis wise

Tested on remaining normal data and all of abnormal data 

Output : Label (normal/abnormal) & metrics for model performance

--Gripper Force,

Trained on 50% of actual location and 50 % of Gripper force of normal data

Tested on remaining normal data and all of abnormal data

Output : Label (normal/abnormal) & metrics for model performance 




Date: Fall 2020 
