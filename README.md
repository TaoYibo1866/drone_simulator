# ���˻�Ӳ���ڻ�����
## ����
```Bash
$ sudo apt-get install ros-kinetic-joint-state-publisher-gui
$ cd ~/catkin_ws/src
$ git clone https://gitee.com/harbin-institute-of-technology-csc/drone_simulator.git
$ cd ~/catkin_ws
$ catkin_make
```
## ���н��
�鿴ģ��
```Bash
$ roslaunch drone_description display.launch
```
![image](https://gitee.com/harbin-institute-of-technology-csc/drone_simulator/raw/master/dji_m100_gimbal_camera_rviz.png)
��׼��Խ����
```Bash
$ roslaunch drone_gazebo jing_zhun_chuan_yue.launch
```
![image](https://gitee.com/harbin-institute-of-technology-csc/drone_simulator/raw/master/jing_zhun_chuan_yue.png)
�칬��������
```Bash
$ roslaunch drone_gazebo tian_gong_zhu_ta.launch
```
��OSDK�������ݻط�
```Bash
$ roslaunch drone_simulator tian_gong_zhu_ta_replay.launch
```
![image](https://gitee.com/harbin-institute-of-technology-csc/drone_simulator/raw/master/tian_gong_zhu_ta_replay.png)