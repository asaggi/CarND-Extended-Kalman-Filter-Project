# Extended Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

In this project we used an kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. We obtained RMSE values that are lower than the tolerance outlined in the project rubric in the function. 


INPUT: values provided by the simulator to the c++ program

["sensor_measurement"] => the measurement that the simulator observed (either lidar or radar)

OUTPUT: values provided by the c++ program to the simulator

["estimate_x"] <= kalman filter estimated position x
["estimate_y"] <= kalman filter estimated position y
["rmse_x"]
["rmse_y"]
["rmse_vx"]
["rmse_vy"]

---

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make` 
4. Run it: `./ExtendedKF `


