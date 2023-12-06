# Autonomous SLAM/Gmapping

#### Dependencies

- Ros Noetic

- Catkin_ws

- Turtlebot3

- Gazebo + rviz

Installation instructions separate from this report. 

Navigate to catkin_ws and run to build the packages:

```
$ catkin_make
```

To launch the simulation, run:

```
$ export TURTLEBOT3_MODEL=burger

$ roslaunch turtlebot3_gazebo turtlebot3_world.launch
```

Then once gazebo opens, use the following to load rviz:

```
$ roslaunch auto_nav turtlebot3_auto_nav.launch
```

Finally, move the robot to a point in space:

```
$ rosrun auto_nav goal_pose.py
```
