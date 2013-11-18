mjpeg_server [![Build Status](https://api.travis-ci.org/RobotWebTools/mjpeg_server.png)](https://travis-ci.org/RobotWebTools/mjpeg_server)
============

#### A ROS Node to Stream Image Topics Via a MJPEG Server
For full documentation, see [the ROS wiki](http://ros.org/wiki/mjpeg_server).

This project is released as part of the [Robot Web Tools](http://robotwebtools.org/) effort.

### License
mjpeg_server is released with a BSD license. For full terms and conditions, see the [LICENSE](LICENSE) file.

### Authors
See the [AUTHORS.md](AUTHORS) file for a full list of contributors.

### Safe operation
In order to ensure that a client can only connect to permitted topics (e.g. to address privacy issues in conjunction with RosWebTools), the server now also accepts a parameter '~topic_wl', listing all white-listed topics. If this parameter is not present, the default behaviour is used.
