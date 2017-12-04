# political5-project3

in this project we communicate with the roomba using ROS in raspberry-pi.

# create workspace 

rosdep update

rosdep install-- from-path src -i -y

catkin_make

source ./devel/setup.bash

pip install pycreate

# how to creat a publisher

cd ~/robot/src

catkin_create_package_sensor_pub rospy

# how to creat suscriber

cd ~/robot/src

catkin_create_package_wheels_sub rospy

# rosdore

cd ~/abdul_work_sapce

source ./devel/setup.bash

export ROS_master_url=http://[pi_ip_address]:1131

export ROS_IP = [pi_ip_address]

roscore package_sensor.py

# terminal

cd ~/robot

source devel/setup.bash

rosrun 

# terminal

cd `/robot

source devel/setup.bash

rosrunpackage_wheels_sub.py

# terminal2

cd `/robot

source devel/setup.bash

rosrun package_sensor_sub.py

