# RADAR_LiDAR_Testing_university_Task

# Objective and Methodology

The study investigates the performance of three different sensors—two LIDAR systems (Velodyne and Blickfeld Cube 1) and one RADAR system (MMWAVCAS-RF-EVM from Texas Instruments)—under clear and foggy conditions. The primary goal is to evaluate the effects of fog on sensor accuracy and range. The analysis involves processing CSV datasets containing sensor readings, computing object distances based on coordinate data, and visualizing results through histograms for comparative analysis.

# Sensor Performance Analysis
Velodyne (LIDAR)

Clear Conditions: Effective within 0–15 meters, with reduced performance from 15–25 meters and complete failure beyond 35 meters.
Foggy Conditions: Effective up to 10–17 meters, after which performance deteriorates sharply.
Blickfeld Cube 1 (LIDAR)

Clear Conditions: Effective up to 15 meters, then degrades, with a maximum range of 30 meters.
Foggy Conditions: Performs slightly better than Velodyne, with effective range up to 20–25 meters, but still significantly impacted by fog.
MMWAVCAS-RF-EVM (RADAR)

Clear Conditions: Superior performance with effective detection up to 37–40 meters, gradual degradation beyond 20 meters.
Foggy Conditions: Maintains effective range up to 35–40 meters, showing a minor initial drop in performance but an overall strong ability to penetrate fog.

# Conclusions
Fog significantly affects LIDAR sensors, reducing their operational range and accuracy.
RADAR sensors exhibit higher resilience to fog, maintaining effective range and accuracy in both conditions.
RADAR outperforms LIDAR in both clear and foggy conditions, making it a preferable choice for applications requiring robustness in adverse weather.


# Clear Condition
![image](https://github.com/user-attachments/assets/899f8d44-01bf-4f95-816e-12f05b686e2f)

# Foggy Condition
![image](https://github.com/user-attachments/assets/ad59ac0c-5e7f-4450-847b-b7a42d9a7c33)

# Results
# SENSOR 3 - MMWAVCAS-RF-EVM (Texas Instruments) - (Radar)
![image](https://github.com/user-attachments/assets/1f78ca4e-63bf-4bac-bdf4-166213320f95)

# SENSOR 2 - Velodyne (Lidar)
![image](https://github.com/user-attachments/assets/f4133439-edaf-4525-a571-d7073c6cb655)

# SENSOR 3 - Blickfeld Cube 1 (Lidar)
![image](https://github.com/user-attachments/assets/1d92b1a9-6e87-4a32-a792-4906d3017ad4)

