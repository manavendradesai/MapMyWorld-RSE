# MapMyWorld-RSE
Project 4 of the Robotics Software Engineering Nanodegree Program at Udacity

## Outcomes -->

- Learnt to implement SLAM using ROS, C++ and Gazebo. Covered SLAM concepts such as occupancy **grid mapping, GraphSLAM and FastSLAM**
- Deployed **RTAB-Map** and used the tele-operation package to drive the mobile robot and build 2D and 3D maps of the environment 

## Directory structure -->

    ├── my_robot                       # my_robot package                   
    │   ├── launch                     # launch folder for launch files
    │   │   ├── RvizLaunch.launch
    │   │   ├── amcl.launch
    │   │   ├── robot_descriptionGoChaseIt.launch
    │   │   ├── worldGoChaseIt.launch
    │   ├── maps                       # folder containing the Gazebo world map and metadata
    │   │   ├── home.yaml
    │   │   ├── map.pgm
    │   ├── model                      # folder containing the Gazebo world model
    │   │   ├── homeGoChaseIt
    │   │   │   ├── model.config
    │   │   │   ├── model.sdf
    │   ├── meshes                     # meshes folder for the lidar sensor
    │   │   ├── hokuyo.dae
    │   ├── urdf                       # urdf folder for xarco files
    │   │   ├── my_robotGoChaseIt.gazebo
    │   │   ├── my_robotGoChaseIt.xacro
    │   ├── worlds                     # world folder for world files
    │   │   ├── homeGoChaseIt
    │   │   ├── homeGoChaseIt.world
    │   │   ├── myApartment
    │   ├── CMakeLists.txt             # compiler instructions
    │   ├── package.xml                # package info
    ├── teleop_twist_keyboard          # Tele-operation package for navigating the mobile robot in Gazebo
    │   ├── CHANGELOG.rst              
    │   ├── CMakeLists.txt             
    │   ├── README.md                  
    │   ├── package.xml                # package info
    │   ├── teleop_twist_keyboard.py   # package info
    ├── media                          # screenshots of the world and the robot
    └── Localization_screenshots       # screenshots showing progression in localizing the mobile robot
