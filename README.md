# pxm411 Navvis Description File
###### This document discusses the use of "rviz" with the joint_state_publisher GUI and without the joint_state_publisher GUI. 
###### The assumption here is that the user already has ROS Melodic, `joint_state_publisher`, and velodyne installed. 
###### The following commands are used with and without the `joint_state_publisher` GUI to use package launch files to view the robot description in `rviz`

## Using `rviz` with `joint_state_publisher` GUI:
### Using the URDF file
> `roslaunch navvis_description navvis_description.launch`
### Using the XARCO file
> `roslaunch navvis_description navvis_description.launch use_xacro:=true`
#
## Using `rviz` without the `joint_state_publisher` GUI: 
### Using the URDF File
> `roslaunch navvis_description navvis_description.launch use_gui:=false`
### Using the XARCO file
> `roslaunch navvis_description navvis_description.launch use_xacro:=true use_gui:=false` 



