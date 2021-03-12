# TIRC_Galileo ROS Package

![](https://img.onl/ZLiQM0)

cd ~ your ros workspace /src
```sh
git clone https://github.com/kubot080301/TIRC_galileo.git
cd ..
```
Then catkin_make and source workspace 

----
Start your ROBOT base driver : 
```sh
roslaunch kubot_bringup bringup.launch
```
If you want get IMU data : 
```sh
roslaunch kubot_bringup bringup_with_imu.launch
```
```sh
rostopic echo /raw_imu
```
and battery voltage:
```sh
rostopic echo /battery_voltage
```
