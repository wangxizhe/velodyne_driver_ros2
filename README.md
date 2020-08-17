# velodyne_driver_ros2
velodyne_driver on ROS2(foxy) Ubuntu20 
## 依赖项安装  
sudo apt install ros-foxy-diagnostic-updater  
sudo apt install libpcap0.8-dev  
  
## 安装方法  
mkdir -p velodyneDriver_ros2/src  
cd velodyneDriver_ros2/src
git clone https://github.com/wangxizhe/velodyne_driver_ros2.git  
cd ..  
colcon build  

## 运行方法  
. install/setup.bash  
ros2 launch velodyne velodyne-all-nodes-VLP16-launch.py 
