![Image](/assets/dp.JPG){:height="50%" width="50%"}

## About Me
------

I am a graduate student in the Robotics Institute at Carnegie Mellon University, pursuing MS in Robotic Systems Development (MRSD). I work on autonomous navigation for quadrotors and ground vehicles, mainly on the control and motion planning side. I am interested in solving these problems using the conventional as well as learning based approaches. I have also worked on LIDAR perception algorithms and deep reinforcement learning for quadrotor navigation. Prior to this, I completed my Bachelor of Technology in Mechanical Engineering from National Institute of Technology Karnataka, Surathkal, India.
Center-aligned
{: .text-center}

## Projects
------

**FlySense - Augmented Reality based assistive technology For safe aerial navigation**  
&nbsp;&nbsp;*MRSD capstone project, August'17-May'18, Carnegie Mellon University*

![Image](/assets/landing_interface.png){:height="50%" width="50%"} ![Image](/assets/quad2.png){:height="50%" width="40%"}

An Augmented Reality (AR) based assistive system that provides complete and enhanced situational awareness through real time visual and audio feedback and enables pilots to navigate safely. FlySense offers a high level of assistance through mapping of surrounding obstacles and low-level autonomy to override bad decisions by the pilot. The entire system is tested in flight using a DJI M100 quadcopter equipped with a Velodyne LIDAR and camera, streaming the required information real time to the Epson BT-300 AR headset worn by the pilot. The obstacle information is projected as a Bird's Eye View, the relevant aerial data for pilot's reference added as a Head's Up Display and finally merged with the First Person View video coming from the onboard camera to complete the FlySense interface. Wearing the AR headset, the pilot is made to control the DJI M-100 quadcopter using the RC controller by only relying on the interface and no direct line of sight with the vehicle.     
[[report]](/assets/TeamC_FinalReport.pdf), [[poster]](/assets/TeamC_Poster.pdf), [[video]](https://youtu.be/h-aslf8awWk), [[website]](https://mrsdprojects.ri.cmu.edu/2017teamc/), [[code]](https://github.com/hks95/flysense_sensing/tree/master)     
------

**Learning control policies for quadcopter navigation with battery constraints**      
&nbsp;&nbsp;*10-703 - Deep Reinforcement Learning and Control, January'18-May'18, Carnegie Mellon University*

Quadcopter UAVs are being heavily deployed in autonomy tasks due to its small size and high maneuverability, thereby enabling them to execute complex trajectories efficiently. However in the context of long range autonomy, these robots are limited in terms of performance due to their battery constraints. This brings forth the need to generate efficient controllers that can enable the quadcopter to operate in a real environment for extended periods with maximum productivity. Through this project, an agent is trained to learn low level control policies (velocity commands) that helps it navigate to a specified goal with minimum battery consumption. The agent is trained in a reinforcement learning setting using the Deep Deterministic Policy Gradient algorithm. We evaluate our algorithm in a simulated environment for mulitple goals and show that the agent learns to navigate with optimal velocities resulting in almost the same mean battery consumption, irrespective of how far or near the goal is.     
[[report]](/assets/deep-rl-final.pdf), [[video]](https://youtu.be/atGmYfytJQA), [[code]](https://github.com/hks95/quad-navigation-drl/tree/indigo_devel)
======

* **Field scale autonomy for vineyards**      
&nbsp;&nbsp;*16-662 - Robot Autonomy, January'18-May'18, Carnegie Mellon University*

A software stack for an autonomous mobile platform for the purposes of navigation within a vineyard. The robot uses onboard sensors to perform localization using a dual EKF approach. A velodyne LIDAR helps the robot perceive non-traversable obstacles in the environment, while a camera assists in detecting the target vineyard row to enter. This information is used to generate a high level global plan using the RRT* algorithm and a local plan using a Timed Elastic Band algorithm, while avoiding static and dynamic obstacles.     
[[report]](/assets/robot-autonomy-final.pdf), [[video]](https://youtu.be/KkF2rET7Z3c), [[code]](https://github.com/hks95/CaveCrawler/tree/global_planning)    

* **Modeling, simulation, and complete control of a quadcopter**    
&nbsp;&nbsp;*BTech major project, August'16-May'17, National Institute of Technology Karnataka*

A research project involving simulation studies on nonlinear dynamics and control of a quadcopter for attitude control and trajectory following. Firstly, a comparative study on linear and nonlinear controllers for the near-hover attitude stabilization of a quadcopter is presented. While the linear methods like PID and the Linear Quadratic Regulator can be successfully applied to the highly nonlinear quadcopter system, the control response and tracking capabilities are not efficient thereby limiting their performance during more aggresive maneuvers. Model based nonlinear controllers prove to be superior in these instances, and one such popular technique - Feedback Linearisation using dynamic inversion is discussed. A PID position controller is then cascaded with this nonlinear attitude controller to enable the quadopter to perform trajectory tracking. The controller receives trajectory commands from a Dijkstra's global planner that acts on a user input occupancy grid, and guides the quadcopter to navigate safely. Based on this work , a paper titled *'Hovering control of a quadcopter using linear and nonlinear techniques'* is accepted for publication in the *'International Journal of Mechatronics and Automation'*   
[[report]](/assets/quadcopter_control_project_report.pdf), [[paper]](/assets/QuadcopterControlFinalVersion.pdf)   

5. **Autonomous navigation stack for a KUKA youBot for a controlled indoor environment**

6. **Data processing for real world user drive cycle generation and fuel economy simulations**

## Useful links

Email: **hsuresh@andrew.cmu.edu** 

Linkedin: **https://www.linkedin.com/in/harikrishnan-suresh**

Github: **hks95**

