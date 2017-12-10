# CarND-Kidnapped-Vehicle-Project

[image1]: ./image/result.png "result"

## The Project results

In this project, I completed unscented Kalman filter in C++ to estimate position and speed of moving object using lidar and radar measurements. 


![alt text][image1]


My px, py, vx, and vy RMSE are less than the required values [.09, .10, 0.40, 0.30]. Changes are made in 
src/ukf.cpp and src/tools.cpp. The code presented here is designed to work with the Udacity term 2 simulation executable, and so cannot
 be run standalone. However, here's some example(data1) output.
