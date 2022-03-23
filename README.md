# robot_b_config (quader_pad with wheel)

it is just like a quaderpad which include wheels each legs has 1 degree of freedom to change the postion I used moveit configuration

Note : - To work with leg oparatin you must install moveit in your workspace hen only you can use

you can download this repository by fallowing bellow steps

cd catkin_ws/src git clone https://github.com/Aravind8967/robot_a_config.git cd .. catkin_make

------------ To see the robot command is ----------------------

roslaunch robot_a_bringup robot_a_bringup.launch

---------------------------- to move the robot command is ----------

rosrun teleop_twist_keyboard teleop_twist_keyboard.py

------------------ for slam and moveit operation ( in another terminal type) ------------

roslaunch robot_a_moveit_config robot_a_moveit_bringup.launch

these are the command to see

this robot has cmd_vel imu laser camera also functionality

---------- you can check publishing topic by ------------

rostopic list

you can check this by publishing

--------------- for imu ----- rostopic echo /imu

---------- for odom ----------- rostopic echo /odom
