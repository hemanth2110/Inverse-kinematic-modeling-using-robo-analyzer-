# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
1.open the roboanalyzer software.
2.select the robot and its degrees of freedom.
3.change the values of X and Y wherever necessary.
4.simulate the model for inverse kinematics.
5.plot the graph between the joints.
6.update the DH parameters of the link configuration and end effector configuration.








### SIMULATION 
 ### RPR ROBOT :
 ![1](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/3a593ea7-e868-445c-adc2-101151b12741)
![2](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/07bb8e5b-9753-4ade-8748-1e81dcb64ffa)
### 3R ROBOT :
![3](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/cb3174fc-2fab-4f40-8ebc-1af64621e46a)

 
 
 
 
 
 
 ### PLOT 
 ### RPR PLOT :
 ![4](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/21e5f344-f3f4-423f-8e2b-19f99fa1df54)
![5](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/43aea02e-fc3b-492c-83d0-ddd5f5442656)

## 3R ROBOT :
![6](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/96e47a6f-77ae-413d-b8cc-bd35cf98de48)
![7](https://github.com/hemanth2110/Inverse-kinematic-modeling-using-robo-analyzer-/assets/121078629/785965a8-5858-4bcd-bad9-2e9088c6383a)




 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
