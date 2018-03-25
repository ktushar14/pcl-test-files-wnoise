# Point Clouds for Degenerate Registration
ICP was used to compute rigid transformations between sonar scan submaps to test for loop-closure constraints in the factor graph formulation of an underwater SLAM framework. This contains code and .pcd files of point clouds created for testing PCL's ICP implementations (point-to-plane, 2D), as well as our own implementation of ICP with an added odometry prior based on odometry information received from the Hovering AUV's AHRS (Attitude and Heading Reference System) + DVL (Doppler Velocity Log) system.
