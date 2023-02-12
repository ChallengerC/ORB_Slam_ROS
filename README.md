# ORB_Slam_ROS
Use ROS to call local camera
调用本地摄像头 
```
roscore
```
```
roslaunch usb_cam usb_cam-test.launch
```
```
 rosrun ORB_SLAM3 Mono /home/czh/catkin_ws/src/ORB_SLAM3/Vocabulary/ORBvoc.txt /home/czh/catkin_ws/src/ORB_SLAM3/Examples/ROS/ORB_SLAM3/Asus.yaml
```

