# Ardupilot-SITL

## Running simulations with ROS2 for Copter

- **Iris Runway**
  ```sh
  ros2 launch ardupilot_gz_bringup iris_runway.launch.py
  ```
- **Iris Maze**
  ```sh
  ros2 launch ardupilot_gz_bringup iris_maze.launch.py
  ```

## Examples
- **Simple Takeoff And Landing**
  This will takeoff the drone and hover over the desired altitude for 15s and land it


## To Execute any of the example
1. Copy the python file into the onboard computer

2. Go to the onboard computer's terminal and replace the `<pythonfile.py>` with your filename and execute the following:
   ```sh
   python <pythonfile.py> --connect /dev/ttyAMA0
   ```
3. Terminal will start receiving all the parameters and code starts executing.
