# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure
```
Step1:
 Use from robomaster import robot
 Step2:
  Choose the x,y,z - axis movement distance(meters)
 Step3:
  Give ep_chassis.move to move straight.
 Step4:
  Give time.sleep() for a break
 Step5:
  Give ep_chassis.drive_speed to have a circular movement
```

## Program
```python
from robomaster import robot
import time

if __name__ == '__main__':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis

    ## Write your code here


    
    ep_robot.close()
```

## MobileRobot Movement Image:

![robo](./img/robomaster.png)

![alt text](image.png)
## MobileRobot Movement Video:

https://youtu.be/kcNoeTvK7wA?feature=shared


## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.


<br/>
<br/>

```
Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College
```
