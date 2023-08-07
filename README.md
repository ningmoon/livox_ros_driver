# 览沃 ROS 驱动程序（简洁版）
[livox_ros_driver English README](https://github.com/Livox-SDK/livox_ros_driver/blob/master/README_EN.md)

[览沃ROS驱动程序中文说明](https://github.com/Livox-SDK/livox_ros_driver/blob/master/README_CN.md)

1. 运行览沃 ROS 驱动程序之前，必须安装 ROS 和 Livox-SDK。
2. 构建览沃 ROS 驱动程序

   ```bash
   git clone https://github.com/Livox-SDK/livox_ros_driver.git ws_livox/src
   cd ws_livox
   catkin_make
   ```
3. 使用如下命令更新当前 ROS 包环境

   `source ./devel/setup.sh`

4. 加载览沃 ROS 驱动
   
   `roslaunch livox_ros_driver livox_lidar_rviz.launch bd_list:="0TFDG3B006H2Z11&1HDDG8M00100191"`
