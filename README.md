# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 









### Robot movements 

![image](https://user-images.githubusercontent.com/104021170/206893091-8d9228ff-a2d8-470c-aeb4-b7dacc1b6502.png)

![image](https://user-images.githubusercontent.com/104021170/206893095-fd3c2dfe-4269-46e7-957a-b68407a0b9f8.png)

![image](https://user-images.githubusercontent.com/104021170/206893104-457ea216-4621-441c-9c94-cf347d537119.png)

![image](https://user-images.githubusercontent.com/104021170/206893107-314ecadf-a6db-4902-97c7-752584546cbb.png)

![image](https://user-images.githubusercontent.com/104021170/206893121-8d3d2742-c010-4567-8cde-69c2e307e8dd.png)

![image](https://user-images.githubusercontent.com/104021170/206893126-70dd7e0c-baba-43db-bb2b-0814e2304415.png)

![image](https://user-images.githubusercontent.com/104021170/206893132-6b25969a-f85e-4444-877e-330bbe39cc5a.png)


OUTPUT:

![image](https://user-images.githubusercontent.com/104021170/206893148-b3c8d9a2-8edf-4f2f-b8d1-9cbc2d429594.png)

![image](https://user-images.githubusercontent.com/104021170/206893155-ddc6c77c-8447-48b4-ae7f-b88e99a65f90.png)


Results: 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully
