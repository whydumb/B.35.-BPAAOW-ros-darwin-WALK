# darwin_control

Darwin OP 로봇을 위한 컨트롤러 인터페이스를 정의하는 ROS 패키지입니다.

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
