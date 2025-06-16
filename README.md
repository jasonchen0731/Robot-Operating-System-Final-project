# Robot-Operating-SystemHW
Robot Operating System Final project  
1.套件建置完成  
2.a) roslaunch myrobot_camera_0507_description gazebo_home.launch 可以生成home世界  
     roslaunch myrobot_camera_0507_description gazebo_myworld.launch 可以生成turtlebot3中的turtlebot3_stage_4世界  
     roslaunch myrobot_camera_0507_description gazebo_turtleworld 可以生成turtlebot3中的turtlebot3_world世界  
  b) roslaunch myrobot_camera_0507_description gazebo_homex2.launch 可以生成home世界與兩個機器人(自行製作機器人與turtlebot3)  
     roslaunch myrobot_camera_0507_description gazebo_worldx2.launch 可以生成turtlebot3中的turtlebot3_stage_1世界與兩個機器人(自行製作機器人與turtlebot3)  
3.a) rosrun myrobot_autodrive robot_autov2.py 可以讓自行製作機器人進行避障  
  b) rosrun myrobot_autodrive robotx2_autov2.py 可以讓自行製作機器人在有兩個機器人的世界進行避障  
     rosrun myrobot_autodrive turtlebot_auto.py 可以讓turtlebot3在有兩個機器人的世界進行避障  
附錄:  
final1_s1100905 為期末考題coding第一題  
final2_s1100905 為期末考題coding第二題且可使用在自行製作機器人與turtlebot3上  
