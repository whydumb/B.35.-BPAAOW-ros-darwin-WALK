# darwin_control

ROS package that defines controller interfaces for Darwin OP robot.

## Install

In order to build this package we suggest using [wstool](http://wiki.ros.org/wstool):

After installing it you can create a new workspace (in the example called `catkin_ws`),
and make it download all the not packaged dependencies:

```
mkdir catkin_ws
cd catkin_ws
wstool init src
wstool merge -t src https://raw.githubusercontent.com/eriol/darwin_control/main/darwin_control.rosinstall
wstool update -t src
```

And then install the packaged dependencies with:
```
rosdep install --from-paths src --ignore-src --rosdistro=${ROS_DISTRO}
```
