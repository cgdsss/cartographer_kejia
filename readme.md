rosservice call /finish_trajectory 0

rosrun map_server map_saver -f 1

rosservice call /write_state ${HOME}/1.pbstream


rosservice call /finish_trajectory 0

rosrun map_server map_saver -f 2

rosservice call /write_state ${HOME}/2.pbstream
