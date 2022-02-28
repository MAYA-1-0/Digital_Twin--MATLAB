# Digital_Twin of the Humanoid in Simulink 
Digital twin is the technical replica of a 3D simulated model in a software and that of a physically built modular prototype.It is a up-to date representation of an actual physical model which replicates every action performed by the 3D simulated model.It is mainly used to evaluate the current position of the robot and receive feedback and predict its future response based on the same. It is basically an actual representation of the robot which is updated by real time data using simulation with respective algorithms,mathematical modelling and PID controls to tune for smooth and optimized performance.
In order to achieve a digital twin of MAYA the team proposes a simulink model of the upper body including head and torso designed and built using MATLAB, The base mobile kinematics is simulated in Gazebo . The 3D model is initially designed in Solidworks and further modified as per requirements and exported in MATLAB and Gazebo.Once exported it is tuned with a feedback control loop using PID controls and synchronized accordingly.

#### Usage/Setup and Requirements

< Coming Soon >

##### MAYA Torso imported in Simulink
![img1](https://github.com/MAYA-1-0/Digital_Twin-MATLAB/blob/main/images/Screenshot%20from%202022-02-28%2020-10-07.png)


##### Simulink Block Diagram
![img2](https://github.com/MAYA-1-0/Digital_Twin-MATLAB/blob/main/images/Screenshot%20from%202022-02-28%2020-10-17.png)

##### Simulink Model Actuated through ROS Topics
![img3](https://github.com/MAYA-1-0/Digital_Twin-MATLAB/blob/main/images/Screenshot%20from%202022-02-28%2020-10-28.png)
