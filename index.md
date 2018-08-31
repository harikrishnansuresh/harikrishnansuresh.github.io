![Image](/assets/dp.JPG){:height="50%" width="50%"}

## About Me
------

<p style='text-align: justify;'> I am a graduate student in the Robotics Institute at Carnegie Mellon University, pursuing MS in Robotic Systems Development (MRSD). I work on autonomous navigation for quadrotors and ground vehicles, mainly on the control and motion planning side. I am interested in solving these problems using the conventional as well as learning based approaches. I have also worked on LIDAR perception algorithms and deep reinforcement learning for quadrotor navigation. Prior to this, I completed my Bachelor of Technology in Mechanical Engineering from National Institute of Technology Karnataka, Surathkal, India. </p>    

## Projects
------

* **FlySense - Augmented Reality based Assistive Technology for Safe Aerial Navigation**  
&nbsp;&nbsp;*MRSD capstone project, Carnegie Mellon University*

![Image](/assets/landing_interface.png){:height="50%" width="50%"} &nbsp; &nbsp; ![Image](/assets/quad2.png){:height="50%" width="40%"}

<p style='text-align: justify;'> An Augmented Reality (AR) based assistive system that provides complete and enhanced situational awareness through real time visual and audio feedback and enables pilots to navigate safely. FlySense offers a high level of assistance through mapping of surrounding obstacles and low-level autonomy to override bad decisions by the pilot. The entire system is tested in flight using a DJI M100 quadcopter equipped with a Velodyne LIDAR and camera, streaming the required information real time to the Epson BT-300 AR headset worn by the pilot. The obstacle information is projected as a Bird's Eye View, the relevant aerial data for pilot's reference added as a Head's Up Display and finally merged with the First Person View video coming from the onboard camera to complete the FlySense interface. Wearing the AR headset, the pilot is made to control the DJI M-100 quadcopter using the RC controller by only relying on the interface and no direct line of sight with the vehicle.</p> 
[[report]](/assets/TeamC_FinalReport.pdf), [[poster]](/assets/TeamC_Poster.pdf), [[video]](https://youtu.be/h-aslf8awWk), [[website]](https://mrsdprojects.ri.cmu.edu/2017teamc/), [[code]](https://github.com/hks95/flysense_sensing/tree/master)     

* **ADAS Function for Pedestrian Collision Avoidance through Evasive Steering Control**  
&nbsp;&nbsp;*Summer Intern - ADAS and Control, Nexteer Automotive*

<p style='text-align: justify;'> An Advanced Driver Assist System (ADAS) feature that allows autonomous vehicles moving at high speed to avoid laterally approaching pedestrians either by braking or evasive steering. The function primarily requires a decision making module that identifies critical targets (if any) from the entire list of detected objects and assigns danger confidence to them. This is done by performing trajectory prediction for the autonomous car using its motion model and also for each of the targets. Based on the most dangerous object, the required maneuver is triggered for which a reference trajctory has to be generated. A polynomial trajectory is planned online based on the current state and desired evasiveness by enforcing the kinematic constraints as boundary conditions. The desired steering wheel angle commands are generated from the trajectory and an angle overlay controller is used to actuate the vehicle. </p> 

* **Learning Control Policies for Quadcopter Navigation with Battery Constraints**      
&nbsp;&nbsp;*10-703 - Deep Reinforcement Learning and Control, Carnegie Mellon University*

![Image](/assets/drl1.png){:height="40%" width="40%"} &nbsp; &nbsp;![Image](/assets/drl2.png){:height="60%" width="50%"}

<p style='text-align: justify;'> Quadcopter UAVs are being heavily deployed in autonomy tasks due to its small size and high maneuverability, thereby enabling them to execute complex trajectories efficiently. However in the context of long range autonomy, these robots are limited in terms of performance due to their battery constraints. This brings forth the need to generate efficient controllers that can enable the quadcopter to operate in a real environment for extended periods with maximum productivity. Through this project, an agent is trained to learn low level control policies (velocity commands) that helps it navigate to a specified goal with minimum battery consumption. The agent is trained in a reinforcement learning setting using the Deep Deterministic Policy Gradient algorithm. We evaluate our algorithm in a simulated environment for mulitple goals and show that the agent learns to navigate with optimal velocities resulting in almost the same mean battery consumption, irrespective of how far or near the goal is. </p>    
[[report]](/assets/deep-rl-final.pdf), [[video]](https://youtu.be/atGmYfytJQA), [[code]](https://github.com/hks95/quad-navigation-drl/tree/indigo_devel)


* **Field Scale Autonomy for Vineyards**      
&nbsp;&nbsp;*16-662 - Robot Autonomy, Carnegie Mellon University*    

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Image](/assets/winebot.png){:height="50%" width="50%"}  

<p style='text-align: justify;'> A software stack for an autonomous mobile platform for the purposes of navigation within a vineyard. The robot uses onboard sensors to perform localization using a dual EKF approach. A velodyne LIDAR helps the robot perceive non-traversable obstacles in the environment, while a camera assists in detecting the target vineyard row to enter. This information is used to generate a high level global plan using the RRT* algorithm and a local plan using a Timed Elastic Band algorithm, while avoiding static and dynamic obstacles. </p>             
[[report]](/assets/robot-autonomy-final-report.pdf), [[video]](https://youtu.be/KkF2rET7Z3c), [[code]](https://github.com/hks95/CaveCrawler/tree/global_planning)    

* **Trajectory Tracking Control of a Quadcopter using Cascaded Linear and Nonlinear Techniques**    
&nbsp;&nbsp;*BTech major project, National Institute of Technology Karnataka*

<p style='text-align: justify;'> A research project involving simulation studies on nonlinear dynamics and control of a quadcopter for attitude control and trajectory following. Firstly, a comparative study on linear and nonlinear controllers for the near-hover attitude stabilization of a quadcopter is presented. While the linear methods like PID and the Linear Quadratic Regulator can be successfully applied to the highly nonlinear quadcopter system, the control response and tracking capabilities are not efficient thereby limiting their performance during more aggresive maneuvers. Model based nonlinear controllers prove to be superior in these instances, and one such popular technique - Feedback Linearisation using dynamic inversion is discussed. A PID position controller is then cascaded with this nonlinear attitude controller to enable the quadopter to perform trajectory tracking. The controller receives trajectory commands from a Dijkstra's global planner that acts on a user input occupancy grid, and guides the quadcopter to navigate safely. </p>          
[[report]](/assets/quadcopter_control_project_report.pdf)

* **Autonomous Navigation Stack for a KUKA YouBot for a Controlled Indoor Environment**    
&nbsp;&nbsp;*Summer research intern, Indian Institute of Technology Madras*

<p style='text-align: justify;'> A software stack for the mobile manipulator platform KUKA youBot for indoor autonomous navigation using a 2D LIDAR. By using a particle filter SLAM algorithm, the youBot generates an occupancy grid of the indoor environment and discovers the traversable spaces. Using a global planner running the Dijkstra's algorithm and a local planner based on Dynamic Window Approach, the robot navigates avoiding both static and dynamic obstacles. </p>     
[[report]](/assets/2D_slam_project_report.pdf)

* **Data Processing for Real World User Drive Cycle Generation and Fuel Economy Simulations**
&nbsp;&nbsp;*Summer intern, Fiat Chrysler Automobiles India*

<p style='text-align: justify;'> Standard emission drive cycles like the New European Drive Cycle, used for measurement of emissions and fuel economy, give results that do not represent field conditions anymore. Thus arises the need for a drive cycle (vehicle speed vs. time) that simulates the actual on-road behavior and accurately predicts the fuel economy as observed by customers. User drive cycles are obtained by processing the data collected from on-road tests using a real time Data Acquisition System. This project involved developing a user drive cycle that processes velocity, acceleration and gear position data to predict the actual fuel consumption of the vehicle. </p>        

## Publications
------

Suresh, H., Sulficar, A. and Desai, V. (2018) ‘Hovering control of a quadcopter using linear and nonlinear techniques’, Int. J. Mechatronics and Automation, Vol. 6, Nos. 2/3, pp.120–129     
[[pdf]](/assets/quadpaper.pdf)  

## Contact Information
------

Email: **hsuresh@andrew.cmu.edu**    
Useful links: [[Linkedin]](https://www.linkedin.com/in/harikrishnan-suresh), [[GitHub]](https://github.com/hks95), [[YouTube]](https://www.youtube.com/channel/UCPn9nip_CHL7ugmE6w0eSSg?view_as=subscriber)

