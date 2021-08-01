# Create-a-Publisher-Node-in-ROS
A python script that publishes to "/move_base_simple/goal" Turtlebot3's topic. It is programmed to navigate the robot to a charging station.

## Create a Package
1. Enter the following commands in the terminal:
```
$ cd ~/catkin_ws/src
$ catkin_create_pkg charging_station std_msgs rospy roscpp
```
2. Build the packages in the catkin workspace:
```
$ cd ~/catkin_ws
$ catkin_make
```
3. Source the generated setup file:
```
$ . ~/catkin_ws/devel/setup.bash
```
## Write The Python script
1. Change the dirictory from the terminal:
```
$ roscd charging_station
```
2. Create a directory named "scripts":
```
$ mkdir scripts
$ cd scripts
```
3. Download the "position.py" file:
```
$ wget 
```
## Run the Node produced from the composed Python script
1. Launch Gazebo and RViz following this link: https://github.com/HebaAlkhorasani/Use-SLAM-map-to-launch-the-navigation.git 
2. Run the node:
```
$ rosrun charging_station position.py
```
