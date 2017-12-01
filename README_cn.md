# AutoRoch

AutoRoch是[Roch](http://wiki.ros.org/Robots/Roch)的一个图形化应用程序.

这个程序收集了Roch一系列的功能模块，例如驱动、跟随、关于SLAM的地图自动探索、导航、远程控制等等。 

如需了解更多内容，请访问: [autoroch](http://wiki.ros.org/autoroch)

## 准备工作

系统需求如下所示:

系统 | 版本 | 
---------------- | ----------------- | 
**Ubuntu** | 14.04.3 |
**ROS** | Indigo |

## 安装

如需安装这个应用程序，你可以查看 ```docs/quick_start/AutoRocht快速指南.pdf```

### ROS层

如果你想要使用这个软件，那么你需要安装如下依赖库:
```
sudo apt-get install ros-indigo-rviz ros-indigo-sensor-msgs ros-indigo-roch-msgs \
                     ros-indigo-nav-msgs ros-indigo-rqt-plot ros-indigo-move-base \
                     ros-indigo-cv-bridge ros-indigo-image-transport ros-indigo-opencv3 
```

### Ubuntu层

安装完成ROS依赖库后，还需要安装:
```
sudo apt-get install libssh2-1-dev libbotan1.10-dev
```

### Roch层
如果想要使用AutoRoch, 你需要在你的Roch电脑上运行如下命令:
```
sudo apt-get install qt4-default
sudo apt-get install qt5-default libssh2-1-dev libbotan1.10-dev
```

安装完成后，双击```ros-indigo-autoroch_*.*.*-0trusty-*_amd64.deb```安装.

## 使用

首先你应该运行如下命令，将应用程序图标放到桌面:
```
 cp /usr/share/applications/AutoRoch.desktop ~/Desktop/
```

然后你将在桌面上找到一个名为```AutoRoch```的应用程序图标,双击启动.

AutoRoch启动完成后,请阅读```/docs/user_manual/AutoRoch用户手册V*_测试版.pdf```使用软件控制Roch.
