# Mushr_workspace

This is fork from racecar_gazebo.
I just added mushr urdf to control the robot.

- Run `roslaunch racecar_gazebo racecar1.launch` to visualize mushr in Gazebo.
- Then, run `rosrun racecar_control keyboard_teleop1.py` to control the robot in Gazebo.
- Parameters of the PID controller are in `racecar_control.yaml`