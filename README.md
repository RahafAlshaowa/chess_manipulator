# Chess Manipulator

A simulation of a FRANKA EMIKA Panda robotic arm programmed to play chess. Gazebo simulation and ROS2 were used to implement this project. 

## Build

Clone the repository to your Ros2 workspace, Inside the workspace build the package

```
colcon build --packages-select chess_manipulator 
. install/setup.bash
```
## Run 
To launch the simulation:
```
ros2 launch chess_manipulator simulation.launch.py
```
To run the example game:
```
ros2 run chess_manipulator example_game
```
## Example
[![Watch the video](https://img.youtube.com/vi/zvH8goUo2EE/maxresdefault.jpg)](https://youtu.be/zvH8goUo2EE)
