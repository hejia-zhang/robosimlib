# RoboSimLib
## Contributing
- Please help contribute this library by adding pull request.
- When you want to add mujoco robot files:
    - Please follow [example reacher](https://github.com/hjzh4/robosimlib/tree/master/robots/mujoco/reacher) to 
    separate robot xml file to robot.file, shared.file, <specific_task>.file.
- If you want to use mocap, please add mocap_statement.xml and <task>_with_mocap.xml, e.g [example sawyer](https://github.com/hjzh4/robotics-sim-files/tree/master/robots/mujoco/sawyer)
## Usage
- Check out this repository as a submodule of your working repository, into robotsimlib
    ```
    $ git submodule add -f https://github.com/hjzh4/robosimlib.git robosimlib
    ```
### Example
```
# Let's say we want to use mujoco sawyer for reach task
from robosimlib.robosimlib_configuration import MUJOCO_ROBOTS_DIR
sawyer_mujoco_file_path = os.path.join(MUJOCO_ROBOTS_DIR, 'sawyer', 'reach.xml')
```
## Content
### Mujoco
- [sawyer](https://github.com/hjzh4/robotics-sim-files/tree/master/robots/mujoco/sawyer)
- [reacher](https://github.com/hjzh4/robosimlib/tree/master/robots/mujoco/reacher)
- [red bin v1](https://github.com/hjzh4/robosimlib/tree/master/objects/mujoco/red_bin_v1)
- [green bin v1](https://github.com/hjzh4/robosimlib/tree/master/objects/mujoco/green_bin_v1)
- [yellow bin v1](https://github.com/hjzh4/robosimlib/tree/master/objects/mujoco/yellow_bin_v1)
### Gazebo
- [red bin](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/red_bin)
- [green bin](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/green_bin)
- [yellow bin](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/yellow_bin)
- [red block](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/red_block)
- [green block](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/green_block)
- [yellow block](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/yellow_block)
- [cafe table](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/cafe_table)
- [target](https://github.com/hjzh4/robotics-sim-files/tree/master/objects/gazebo/target)
