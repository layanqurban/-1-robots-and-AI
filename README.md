# -1-robots-and-AI
how to install ROS on ubuntu
 - install and run the UBUNTU operating system
 - add the ros repository in the source.list of ubuntu
    sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release  sc)main" > /etc/apt/sources.list.d/ros-latest.list'
 - add access key
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654"
 - update the packages list 
sudo apt update
 - desktop-full ROS Installation
sudo apt install ros-noetic-desktop-full
 - setup the environment
source /opt/ros/noetic/setup.bash
 - install tools and other dependencies for building ROS packages
sudo apt install python3-rosdep python3-rosinstall python3-rosinstall-generator python3-wstool build-essential
 
