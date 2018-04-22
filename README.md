# Extended Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

In this project we used an kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. We obtained RMSE values that are lower than the tolerance outlined in the project rubric in the function. 


INPUT: values provided by the simulator to the c++ program

["sensor_measurement"] => the measurement that the simulator observed (either lidar or radar)

OUTPUT: values provided by the c++ program to the simulator

["estimate_x"] <= kalman filter estimated position x.  
["estimate_y"] <= kalman filter estimated position y.  
["rmse_x"].   <= RMSE of position x.  
["rmse_y"].  <= RMSE of position y.  
["rmse_vx"].   <= RMSE of Velocity x.  
["rmse_vy"].  <= RMSE of Velocity y.  



## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make` 
4. Run it: `./ExtendedKF `


## Results

In various different tests Extended Kalman Filter produces the below results. The x-position is shown as 'px', y-position as 'py', velocity in the x-direction is 'vx', while velocity in the y-direction is 'vy'. Residual error is calculated by mean squared error (MSE).

###Data Set One.   

Input  | MSE
------------- | -------------
px  | 0.103
py  | 0.088
vx  | 0.594
vy  | 0.464

![Test One Visualization](https://github.com/asaggi/CarND-Extended-Kalman-Filter-Project/blob/master/Docs/Data_Set1.png "Test One Visualization")
---

###Data Set Two.   

Input  | MSE
------------- | -------------
px  | 0.073
py  | 0.097
vx  | 0.426
vy  | 0.498

![Test Two Visualization](https://github.com/asaggi/CarND-Extended-Kalman-Filter-Project/blob/master/Docs/Data_Set2.png "Test Two Visualization")