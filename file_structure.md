## Folder structure ![some-changes](https://img.shields.io/badge/some_changes-yellow)

```
.
└── tortoisebot/
    ├── tortoisebot_control/
    │   ├── src/
    |   |   └── tortoisebot_teleop_key.py
    |   ├── CMakeLists.txt
    │   └── package.xml
    |
    ├── tortoisebot_description/
    |   ├── gazebo/
    |   |   ├── tortoisebot_materials.gazebo
    |   |   ├── tortoisebot_physcis.gazebo
    |   |   └── tortoisebot_plugins.gazebo
    |   ├── launch/
    |   |   ├── display.launch
    |   |   ├── gazebo.launch
    |   |   └── rviz.launch
    |   ├── meshes/
    |   |   ├── base_link.stl
    |   |   ├── camera.stl
    |   |   ├── caster.stl
    |   |   ├── imu.stl
    |   |   ├── lidar_body.stl
    |   |   ├── lidar_bottom.stl
    |   |   ├── lidar_motorend.stl
    |   |   ├── lidar_top.stl
    |   |   ├── lidar_left.stl
    |   |   └──  lidar_right.stl
    |   ├── rviz/
    |   |   ├── display.rviz
    |   |   └── urdf.rviz
    |   ├── urdf/
    |   |   ├── materials.xacro
    |   |   └── tortoisebot.xacro
    |   ├── CMakeLists.txt
    |   └── package.xml
    |
    ├── tortoisebot_description/
    |   ├── gazebo/
    |   |   ├── tortoisebot_materials.gazebo
    |   |   ├── tortoisebot_physcis.gazebo
    |   |   └── tortoisebot_plugins.gazebo
    |   ├── launch/
    |   |   ├── display.launch
    |   |   ├── gazebo.launch
    |   |   └── rviz.launch
    |   ├── meshes/
    |   |   ├── base_link.stl
    |   |   ├── camera.stl
    |   |   ├── caster.stl
    |   |   ├── imu.stl
    |   |   ├── lidar_body.stl
    |   |   ├── lidar_bottom.stl
    |   |   ├── lidar_motorend.stl
    |   |   ├── lidar_top.stl
    |   |   ├── lidar_left.stl
    |   |   └──  lidar_right.stl
    |   ├── rviz/
    |   |   ├── disolay.rviz
    |   |   └── urdf.rviz
    |   ├── urdf/
    |   |   ├── materials.xacro
    |   |   └── tortoisebot.xacro
    |   ├── CMakeLists.txt
    |   └── package.xml
    |   
    ├── tortoisebot_firmware/
    |   ├── config/
    |   |   ├── demo.rviz
    |   |   └── lidar.rviz
    |   ├── launch/
    |   |   ├── bringup.launch
    |   |   ├── joy_control.launch
    |   |   ├── server_bringup.launch
    |   |   ├── tortoisebotlidarS2.launch
    |   |   └── tortoisebotlidarX4.launch
    |   ├── scripts/
    |   |   ├── 1ms.py
    |   |   ├── diff.py
    |   |   ├── differential.py
    |   |   └── odom.py
    |   ├── CMakeLists.txt
    |   └── package.xml
    |
    ├── tortoisebot_gazebo/
    |   ├── launch/
    |   |   ├── tortoisebot_docking.launch
    |   |   ├── tortoisebot_empty_world.launch
    |   |   └──  tortoisebot_playground.launch
    |   ├── models/
    |   |   ├── crossing_obstacle/
    |   |   ├── docking_arena/
    |   |   ├── docking_station/
    |   |   ├── home_obstacle/
    |   |   ├── parking_obstacle/
    |   |   ├── playground/
    |   |   ├── signal_obstacle/
    |   |   ├── stop_obstacle/
    |   |   └── turn_obstacle/
    |   ├── worlds/
    |   |   ├── docking_playground_left.world
    |   |   ├── docking_playground_right.world
    |   |   ├── empty_playground.world
    |   |   ├── tortoisebot_playground.world
    |   |   └── tortoisebot_playground_light.world
    |   ├── CMakeLists.txt
    |   └── package.xml
    |
    ├── tortoisebot_navigation/
    |   ├── launch/
    |   |   ├── amcl.launch
    |   |   ├── move_base.launch
    |   |   ├── sim_move_base.launch
    |   |   ├── tortoisebot_navigation.launch
    |   |   └── tortoisebot_sim_navigation.launch
    |   ├── maps/
    |   |   ├── docking.pgm
    |   |   ├── docking.yaml
    |   |   ├── my_map.pgm
    |   |   ├── my_map.yaml
    |   |   ├── playground_map.pgm
    |   |   ├── playground_map.yaml
    |   |   ├── sim_map.pgm
    |   |   └── sim_map.yaml
    |   ├── param/
    |   |   ├── costmap_common_params.yaml
    |   |   ├── dwa_local_planner_params.yaml
    |   |   ├── global_costmap_params.yaml
    |   |   ├── local_costmap_params.yaml
    |   |   ├── move_base_params.yaml
    |   |   └── sim_dwa_local_planner_params.yaml
    |   ├── rviz/
    |   |   └── tortoisebot_navigation.rviz
    |   ├── CMakeLists.txt
    |   └── package.xml
    |
    └── tortoisebot_slam/
        ├── config/
        |   └── gmapping_params.yaml
        ├── launch/
        |   ├── map_saver.launch
        |   ├── tortoisebot_slam.launch
        |   └── view_sensors.launch
        ├── rviz/
        |   ├── mapping.rviz
        |   ├── sensors.rviz
        |   └── tortoisebot_gmapping.rviz
        ├── CMakeLists.txt
        └── package.xml

```
