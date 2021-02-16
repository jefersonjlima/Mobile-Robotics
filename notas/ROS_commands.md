

# Install

* [VM ROS Kinect](https://drive.google.com/file/d/1kx6gNaoGllKjE--0rbW7RSWCN76aVKSN/view)

$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make



# Class 2
geometry_msgs/Twist
rostopic list
rosmsg show turtlesim/Pose
rostopic pub /turtle1/cmd_vel geometry_msgs/Twist -- '[2.0, 0.0, 0.0]' '[0.0, 0.0, 1.8]'
rosrun rqt_graph rqt_graph
rostopic info /turtle1/cmd_vel
rosmsg show geometry_msgs/Twist

catkin_create_pkg beginner_tutorials std_msgs rospy roscpp
catkin_create_pkg my_pkg message_generation rospy
