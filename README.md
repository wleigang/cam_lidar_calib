# cam_lidar_calib

说明:
    该程序是从autoware分离出来的相机-激光雷达联合标定ros功能包。

安装：
1.安装nlopt:
    git clone git://github.com/stevengj/nlopt
    cd nlopt
    mkdir build
    cd build
    cmake ..
    make
    sudo make install

2.下载该程序到自己的ROS工作空间中，使用catkin_make编译
3.执行source devel/setup.bash

运行:
1.开启终端，执行roscore
2.另开启一终端，执行rosrun calibration_camera_lidar calibration_toolkit
