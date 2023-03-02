# Implementation of Error State - Extended Kalman Filter

Note: This was my practice implementation for course

Each element of the data dictionary is stored as an item from the data dictionary, which we will store in local variables, described by the following:

gt: Data object containing ground truth. with the following fields:

a: Acceleration of the vehicle, in the inertial frame

v: Velocity of the vehicle, in the inertial frame

p: Position of the vehicle, in the inertial frame

alpha: Rotational acceleration of the vehicle, in the inertial frame

w: Rotational velocity of the vehicle, in the inertial frame

r: Rotational posi# State_Estimation_For_Autonomous_Vehicles
2
state estimation for autonomous vehicle using error state extended Kalman FIlterstion of the vehicle, in Euler (XYZ) angles in the inertial frame

_t: Timestamp in ms.

imu_f: StampedData object with the imu specific force data (given in vehicle frame).

data: The actual data

t: Timestamps in ms.

imu_w: StampedData object with the imu rotational velocity (given in the vehicle frame).

data: The actual data

t: Timestamps in ms.

gnss: StampedData object with the GNSS data.

data: The actual data

t: Timestamps in ms.

lidar: StampedData object with the LIDAR data (positions only).

data: The actual data

t: Timestamps in ms.

![ES_EKF-ABSTRACT drawio pdf](https://user-images.githubusercontent.com/81559218/222405408-18b6d4aa-5cd5-417d-b158-56bf0da6b967.jpg)


