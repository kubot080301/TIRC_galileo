# TIRC_galileo

cd ~your ros workspace /src
~/src/ git clone https://github.com/kubot080301/TIRC_galileo.git

then 

cd ros workspace
catkin_make

---------------------

roslaunch kubot_bring bringup.launch

rostopic echo /battery_voltage
