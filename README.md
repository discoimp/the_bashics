# the_bashics
A collection of the missing Bash Instructions. Help is often easy to find up to a certain point...
### Create a basic catkin workspace
```
sudo apt update && sudo apt install -y python3-osrf-pycommon python3-catkin-tools
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws
catkin config --init --mkdirs --extend /opt/ros/$ROS_DISTRO --merge-devel --cmake-args -DCMAKE_BUILD_TYPE=Release
```
### Next...
