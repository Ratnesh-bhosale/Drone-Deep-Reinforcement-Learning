# Drone-Deep-Reinforcement-Learning

## Dataset:

Dataset - 'Package Delivery Quadcopter Delivery Dataset' by Carnegie Mellon University.

-----------------------------------------
DATA DESCRIPTION FOR: [parameters.csv]
-----------------------------------------
<create sections for each dataset included>


1. Number of variables: 7


2. Number of cases/rows: 209 


3. Missing data codes: The dataset has no missing data, but in the case of missing codes, the dataset would use "NA" to denote missing data.


4. Variable List

    A. Name: flight
  
       Description: an integer that represents the code of the flight performed. A flight is defined as the data set recorded from the take-off to landing in a predefined route.

    B. Name: speed
  
       Description: programmed horizontal ground speed during cruise in meters per second (m/s).

    C. Name: payload
  
       Description: mass of the payload attached to aircraft in grams (g). The payload used was confined in a standard USPS Small Flat Rate Box.

    D. Name: altitude
  
       Description: predefined altitude in meters (m). The aircraft takes off vertically until it reaches the preset altitude.

    E. Name: date
  
       Description: when the flight was conducted in the YYYY-MM-DD format

    F. Name: local_time

       Description: local time when the flight started in the 24:00-hour format.

    G. Name: route
  
       Description: A predefined path followed by the aircraft. Routes R1 to R7 indicate flights where the drone completed a cruise movement. The differences among routes R1 to R7 reflect variations on the starting point or variations on the altitude during cruise. The differences among routes can be assessed by plotting variables position_x, position_y and position_z. Routes A refer to ancillary ground tests where the drone remained on the ground and did not take off. Route A1 refers to a test with the drone running with no propellers and no motor movement; Route A2 to a test with the drone running with no propellers and minimum motor movement; and Route A3 to a test with the drone running with propellers and minimum motor movement. Route H refers to a test with the drone hovering with no horizonal movement. In summary:  
  
	R1 to R7 = full flights completing a cruise movement;
  
	A1 = Ancillary ground test with no propellers and no motor movement;
  
	A2 = Ancillary ground test with no propellers and minimum movement; 
  
	A3 = Ancillary ground test with propellers and minimum movement;
  
	H = Hover test with no horizontal movement. 
  
  
  
  -----------------------------------------
DATA DESCRIPTION FOR: [flights.csv]
-----------------------------------------
This file combines the data avaliable in flights.zip and parameters.csv in a single CSV file. 

1. Number of variables: 28


2. Number of cases/rows: 257,896.


3. Missing data codes: The dataset has no missing data, but in the case of missing codes, the dataset would use "NA" to denote missing data.


4. Variable List
    A. Name: flight
  
       Description: an integer that represents the code of the flight performed. A flight is defined as the data set recorded from the take-off to landing in a predefined route.

    B. Name: time
  
       Description: Time elapsed in flight in seconds (s).

    C. Name: wind_speed
  
       Description: airspeed provided by the anemometer in meters per second (m/s).

    D. Name: wind_angle
  
       Description: angle in degrees (deg) of the air flowing through the anemometer with respect to the north.

    E. Name: battery_voltage
  
       Description: system voltage in Volts (V) measured immediately after the battery.

    F. Name: battery_current
  
       Description: system current in Ampere (A) measured immediately after the battery.

    G. Name: position_x
  
       Description: longitude of the aircraft in degrees (deg).

    H. Name: position_y
  
       Description: latitude of the aircraft in degrees (deg).

    I. Name: position_z
  
       Description: altitude of the aircraft in meters (m) with respect to the sea-level.

    J. Name: orientation_x; _y; _z; _w
  
       Description: aircraft orientation in quaternions.

    K. Name: velocity_x; _y; _z
  
       Description: velocity components of ground speed in meters per second (m/s).

    L. Name: angular_x; _y; _z
  
       Description: angular volocity components in radians per second (rad/s).

    M. Name: linear_acceleration_x; _y; _z
  
       Description: ground acceleration in meters per squared second (m/s^2).

    N. Name: speed
  
       Description: programmed horizontal ground speed during cruise in meters per second (m/s).

    O. Name: payload
  
       Description: mass of the payload attached to aircraft in grams (g). The payload used was confined in a standard USPS Small Flat Rate Box.

    P. Name: altitude
  
       Description: predefined altitude in meters (m). The aircraft takes off vertically until it reaches the preset altitude.

    Q. Name: date
  
       Description: when the flight was conducted in the YYYY-MM-DD format

    R. Name: local_time
  
       Description: local time when the flight started in the 24:00-hour format.

    S. Name: route
  
       Description: A predefined path followed by the aircraft. Routes R1 to R7 indicate flights where the drone completed a cruise movement. The differences among routes R1 to R7 reflect variations on the starting point or variations on the altitude during cruise. The differences among routes can be assessed by plotting variables position_x, position_y and position_z. Routes A refer to ancillary ground tests where the drone remained on the ground and did not take off. Route A1 refers to a test with the drone running with no propellers and no motor movement; Route A2 to a test with the drone running with no propellers and minimum motor movement; and Route A3 to a test with the drone running with propellers and minimum motor movement. Route H refers to a test with the drone hovering with no horizonal movement. In summary:   
  
	R1 to R7 = full flights completing a cruise movement;
  
	A1 = Ancillary ground test with no propellers and no motor movement;
  
	A2 = Ancillary ground test with no propellers and minimum movement; 
  
	A3 = Ancillary ground test with propellers and minimum movement;
  
	H = Hover test with no horizontal movement.      
  
