# Gazebo9_Ubuntu-16.04


## Delete Gazebo7

    sudo apt-get remove gazebo7
    sudo apt-get autoremove
    
## Install Gazebo9
    
    sudo sh -c 'echo "deb http://packages.osrfoundation.org/gazebo/ubuntu-stable `lsb_release -cs` main" > /etc/apt/sources.list.d/gazebo-stable.list'
    wget http://packages.osrfoundation.org/gazebo.key -O - | sudo apt-key add -
    sudo apt-get update
    sudo apt-get install libgazebo9-dev
    sudo apt-get install gazebo9
    
    sudo apt-get install ros-kinetic-gazebo9-ros-pkgs ros-kinetic-gazebo9-ros-control

    sudo apt-get install ros-kinetic-robot-state-publisher
    sudo apt-get install ros-kinetic-rviz
