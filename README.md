# navigation-using-Turtlebot3-SLAM


## Install ROS on Remote PC

> > `sudo apt update`
> > `sudo apt upgrade`
> > `wget https://raw.githubusercontent.com/ROBOTISGIT/robotis_tools/master/install_ros_noetic.sh`
> > `chmod 755 ./install_ros_noetic.sh `
> > `bash ./install_ros_noetic.sh`


## Install Dependent ROS Packages

> > `sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \ros-noetic-teleoptwist-keyboard ros-noetic-laser-proc \ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \ros-noetic-rosserial-python ros-noetic-rosserial-client \ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \ros-noetic-compressed-image-transport ros-noetic-rqt* ros-noetic-rviz \ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-markers`


## Install TurtleBot3 Packages

> > `sudo apt install ros-noetic-dynamixel-sdk`

> > `sudo apt install ros-noetic-turtlebot3-msgs`

> > `sudo apt install ros-noetic-turtlebot3`


## Launch Simulation World
> > `export TURTLEBOT3_MODEL=burger`
> > `roslaunch turtlebot3_gazebo turtlebot3_world.launch`


# image for the output:
<img width="958" alt="Screenshot 2022-08-11 115659" src="https://user-images.githubusercontent.com/107888642/184114525-7ad2d385-d02e-411c-ad38-229cdbe09964.png">
