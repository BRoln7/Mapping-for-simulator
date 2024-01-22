# Mapping-for-simulator

After establishing the gazebo simulate scene, use this project to get the map
```
roslaunch gazebo_demo gazebo_env.launch
roslaunch nav_demo nav01_slam.launch
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

When the map is established 
```
roslaunch nav_demo nav02_map_save.launch
```