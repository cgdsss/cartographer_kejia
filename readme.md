### Install
http://note.youdao.com/noteshare?id=35bc572d4d2b67b56ea6310d392f3f97
### Rosbag datas 
https://pan.baidu.com/s/1BOmIxIsTsqUSEoJEzgqZjw#list/path=%2F
### CMD
> rosservice call /finish_trajectory 0

> rosrun map_server map_saver -f 1

> rosservice call /write_state ${HOME}/1.pbstream

> roslaunch cartographer_kejia localization_lidar_2d.launch load_state_filename:=${HOME}/1.pbstream
