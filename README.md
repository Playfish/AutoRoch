# AutoRoch

AutoRoch is a gui application for [Roch](http://wiki.ros.org/Robots/Roch).

This program collects a series of function modules of Roch, such as driver, follower, auto explore for SLAM, navigation, remote teleop etc. 

For more information please visit: [autoroch](http://wiki.ros.org/autoroch)

## Preparation

Required Systems described as follows:

System | Version | 
---------------- | ----------------- | 
**Ubuntu** | 14.04.3 |
**ROS** | Indigo |

Required software:

Software  | Version  |
--------- | -------- |
g++ & gcc | 4.9 and above |
OpenCV | 2.4.8 |

## Installation

For install this app you can checkout ```docs/quick_start/AutoRocht¿ìËÙÖ¸ÄÏ.pdf```

### ROS Layer

If you want to use this software and you should install under dependency libraries:
```
sudo apt-get install ros-indigo-rviz ros-indigo-sensor-msgs ros-indigo-roch-msgs ros-indigo-nav-msgs ros-indigo-rqt-plot ros-indigo-move-base ros-indigo-cv-bridge ros-indigo-image-transport ros-indigo-opencv3 
```

### Ubuntu Layer

After install ROS libraries and you should install under:
```
sudo apt-get install libssh2-1-dev libbotan1.10-dev
```

### Roch Layer
If you wanne use AutoRoch, you should typing under command on your Roch computer:
```
sudo apt-get install qt4-default
sudo apt-get install qt5-default libssh2-1-dev libbotan1.10-dev
```

And then double-click ```ros-indigo-autoroch_*.*.*-0trusty-*_amd64.deb``` for install.

## Usage

For using you should do following command at first:
```
 cp /usr/share/applications/AutoRoch.desktop ~/Desktop/
```

Then you can find a start icon for ```AutoRoch``` on your Desktop, double click for startup.

After startup AutoRoch, please read ```docs/user_manual/AutoRoch用户手册V*.*.*.pdf``` for using.
