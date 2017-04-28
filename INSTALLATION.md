# Installation

 - Ubuntu 16.04
 - ROS Kinetic
 - Gazebo 7
 - catkin_ws

```
cd ~/catkin_ws/src/
sudo apt-get install ros-kinetic-navigation
sudo apt-get install ros-kinetic-ackermann-msgs
sudo apt-get install ros-kinetic-dr-base
sudo apt-get install ros-kinetic-joystick-drivers
git clone https://github.com/ros-planning/navigation.git
git clone https://github.com/ros-teleop/twist_mux.git
git clone https://github.com/ros-perception/slam_gmapping.git
git clone https://github.com/ros-perception/openslam_gmapping.git
git clone https://github.com/fnaser/catvehicle.git
git clone https://github.com/gkouros/ackermann-drive-teleop.git
git clone https://github.com/ros-drivers/driver_common
//git clone https://github.com/ros-drivers/joystick_drivers.git
catkin_make
git clone https://github.com/RobotnikAutomation/robotnik_msgs.git
git clone https://github.com/RobotnikAutomation/robotnik_sensors.git
git checkout kinetic-devel
git clone https://github.com/fnaser/rbcar_common.git
git checkout kinetic-devel
git clone https://github.com/fnaser/rbcar_sim.git
git checkout kinetic-devel
//git clone https://github.com/tu-darmstadt-ros-pkg/hector_gazebo.git
//git checkout kinetic-devel
catkin_make
```

# Test

```
roslaunch rbcar_sim_bringup rbcar_complete.launch
```
