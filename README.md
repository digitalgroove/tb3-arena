# TB3 Gazebo Arena

tb3-arena is a Gazebo simulation with turtlebot 3 for recognizing AR Tags

**Author:** FH Aachen, ROS Summer School 2018

![demo-1](https://github.com/digitalgroove/tb3-arena/blob/master/readme-images/arena.png)

## Requirements
* **ROS Kinetic + Gazebo**
* tb3_description (URDF file of turtlebot 3)
* _Joy Package (optional)_
* _RQT (optional)_

## Installation

If you have an active ROS workspace, clone or download the repository into the src directory of your workspace:
```
$ cd ~/catkin_ws/src
$ git clone https://github.com/digitalgroove/tb3-arena.git
```

Next install missing dependencies using rosdep install:
```
$ cd ~/catkin_ws
$ rosdep install --from-paths src --ignore-src --rosdistro=kinetic -y
```

Build:
```
$ cd ~/catkin_ws
$ catkin_make
```

If you haven’t already, the following line can be added to your .bashrc to auto-source all new terminals:
```
source ~/catkin_ws/devel/setup.bash
```


## Usage

```
$ roslaunch tb3_arena tb3_arena.launch
```

In a new terminal tab you can launch rqt:

```
$ rqt
```
Then in the Plugins menu, select "Robot Tools", and "Robot Steering".




## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

