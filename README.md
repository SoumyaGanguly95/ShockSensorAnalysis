# Task Shock Sensor:

## Background:
With the help of shock sensors, we want to detect for our customers if and when an incident (shock)
has occurred which has led to trailer damage and we are also providing some insights to the customer
from the data. So, your task is to perform some analysis and detect the different modality options that
the trailer is going through, meaning if the trailer is transported on the road, the rail, or via ship and if
it is driving or standing based on the shock and gps data provide to you.

## Tasks:
1. Read and perform data cleaning (e.g., As this is also a timeseries data, please consider usual
preprocessing steps to clean the data)
2. Apply Kalman filter to the accelerometer and gps data
3. Perform data analysis and come up with some ideas about the modality where the trailer can
be (e.g., finding patterns or clusters in the data)
4. (Optional) The below example graph shows how 3-dimensional accelerometer data will looks
like in the plots. The coupling and decoupling patterns in the graph are hand labelled and want
to automate this process by recognizing this pattern using Machine learning and Deep learning.
Consider the data is timeseries. Any ideas and insights will be appreciated.

## Datasets
#### Variables and its meaning:

#### Shock:
Timestamp:- Time at which the data is collected (In unix timestamp)
AccelX :- Represents the acceleration in the horizontal direction, typically from front to back or vice
versa
AccelY :- Represents the acceleration in the lateral direction, typically from left to right or vice versa
AccelZ :- Represents the acceleration in the vertical direction, typically from bottom to top or vice versa
GyroX :- Represents rotation around the horizontal axis, typically referred to as roll
GyroY :- Represents rotation around the lateral axis, typically referred to as pitch
GyroZ :- Represents rotation around the vertical axis, typically referred to as yaw
Temperature:- Temperature of the sensor

** Accelerometer and Gyroscope can provide valuable information about the orientation, movement,
and position of an object in three-dimensional space

#### GPS:
Date:- Data collected date
Time:- Time at which the data is collected
Latitude:- Latitude measures the distance north or south of the equator
Longitude:- Longitude measures the distance east or west of a prime meridian
Speed:- Speed of the trailer (in knots)
Track Angle :- Refers to the direction in which a vehicle is moving
Magnetic Variation :- Don’t have to worry about it as we are not focusing this and also no data available

*** Together, latitude and longitude coordinates provide a precise way to locate any point on the
Earth's surface