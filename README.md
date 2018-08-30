# TB3 Gazebo Package

tb3_gazebo is a Gazebo simulation with turtlebot 3 for recognizing AR Tags.

## Installation

### Requirements
* Joy Package (optional)
* RQT (optional)


`$ sudo apt-get install ros-kinetic-joystick-drivers`

## Usage

```
$ roslaunch tb3_gazebo tb3_gazebo.launch
```

In a new terminal tab you can launch rqt:

```
$ rqt
```
In the Plugins menu, select "Robot Tools", then "Robot Steering".

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
