# RPLidar_Foxy
Package for RPLidar A1 M8 on Ros2 Foxy  


ros2 launch sllidar_ros2 view_sllidar_a1_launch.py

Check where the lidar is connected on system ( Linux )  
lsusb - to check whether connection appears
Shows as Silicon Labs CP210x UART Bridge  

sudo dmesg | grep tty - to check which port 
Gives the number of serial port the lidar is connected to. THis might change at system reboot.

Might need to change permissions once connected  
sudo chmod 777 /dev/ttyUSB0
