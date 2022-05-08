# Use of different pcl filters in perception_pcl package 

[![Build Status](https://travis-ci.org/ros-perception/perception_pcl.svg?branch=melodic-devel)](https://travis-ci.org/ros-perception/perception_pcl)

PCL (Point Cloud Library) ROS interface stack. PCL-ROS is the preferred
bridge for 3D applications involving n-D Point Clouds and 3D geometry
processing in ROS.


## ANYmal_C Passthrough Filter
Added a launch file for ANYmal_C robot for filtering of self colliding points.

## Launch
```
roslaunch filters anymal_c_pass_through_filter.launch
```

## ANYmal_C Voxelgrid Filter
Added a launch file for ANYmal_C robot for random filtering points.
```
roslaunch filters anymal_c_voxel_grid_filter.launch
```

## Wiki
Full Documentation can be found on: http://wiki.ros.org/pcl_ros/Tutorials/filters
