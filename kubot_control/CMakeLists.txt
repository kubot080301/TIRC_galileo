cmake_minimum_required(VERSION 2.8.3)
project(kubot_control)

find_package(catkin REQUIRED dynamic_reconfigure)

##     and list every .cfg file to be processed
generate_dynamic_reconfigure_options(
   cfg/CalibrateAngular.cfg
   cfg/CalibrateLinear.cfg
)