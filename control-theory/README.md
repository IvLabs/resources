# Control Theory

## Resources
### Classical Control
* [Classical Control Theory](https://www.youtube.com/watch?v=oBc_BHxw78s&list=PLUMWjy5jgHK1NC52DXXrriwihVrYZKqjk) by Brian Douglas.                  
  **_Why this lecture series? :_** 
This collection of videos is intended to supplement a first-year controls class, not replace it. Here the goal will to take specific concepts in controls and expand on them to provide an intuitive understanding which will ultimately make one a better controls engineer.
Let's take an example of a system that we want to control, say a simple pendulum (the most basic example), suppose we want the pendulum to go upright and stay there, well how do we achieve that? The most basic approach is using the knowledge from control systems to make it stay upright and be able to handle external disturbances for robustness.

* [Control Bootcamp](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m) by Steve Brunton.                                      
  **_Series info :_** This course provides a rapid overview of optimal control (controllability, observability, LQR, Kalman filter, etc.).  It is not meant to be an exhaustive treatment, but instead provides a high-level overview of some of the main approaches, applied to simple examples in Matlab.  
  
##### Note:- For beginners, It is recommended to first go through Brian Douglas (till video 27) course before starting Steve Brunton's course.


* [Control of Mobile Robots](https://www.coursera.org/learn/mobile-robot/home/welcome) by Dr. Magnus Egerstedt.                          
  **_For whom ?:_** Whoever wants to explore the field of Control Theory, Motion, or path planning should surely have a look at this course to get a basic overview. This course will focus more on differential drive robots.                                                                  
**_What's good about this course ?:_** It is fairly different from the general long lectured continuous courses, it maintains a very good balance between theory and its implementation. The concepts are explained excellently using some elegant analogies.                                                     
**_Course info:_** Course focuses on the problem of establishing control over a robot with the pursuit of making it move safely and optimally. The course covers the classic PID control and its applications in controlling a differential drive robot and then moves on to cover few concepts from the Classical Control Theory which helps span principles and fundamentals applicable for control of almost all types of dynamical systems.
 
 
#### Graduate level: 
* [Underactuated Robotics](http://underactuated.csail.mit.edu/Spring2020/) by Dr. Russ Tedrake.                                                      
**_Course info:_** Take a few examples like trajectories of a quadrotor being generated to play a game of pong, Or maybe a humanoid performing a backflip, Or for a simple case make an Acrobot stay upright. In all these cases we can observe that the control algorithms are exploiting the dynamics to perform a task no matter how bizarre it is. Well, this course will help you exploit those dynamics of any given system to perform tasks that may seem impossible from the classical control theory point of view. The course covers techniques like Dynamic Programming, LQR, Lyapunov Analysis, Trajectory Optimization, Model Predictive Control, Motion Planning as Search, Pixels to Torques, Robust and Stochastic Control to State Estimation, Reinforcement Learning and few other techniques

##### Note:- For beginners, It is recommended to first go through Brian Douglas (till video 27) course before starting Steve Brunton's course.


### Specific Control Methods
#### PID control
* [Understanding PID control](https://www.youtube.com/watch?v=wkfEZmsQqiA&list=PLn8PRpmsu08pQBgjxYFXSsODEF3Jqmm-y) from MATLAB.

#### Sliding Mode Control
* [Lecture](https://www.youtube.com/watch?v=v2CNRxG081w&list=PLJmxjP-2T4kthW4VjZn033DYF7Kp_ndt3) by Sarah Spurgeon.
 
#### Adaptive Control
* [Non-Linear & Adaptive Control](https://nptel.ac.in/courses/108/102/108102113/) (Nptel) lecture by Dr. Shubendu Bhasin.

#### Pure Pursuit controller
* [Pure pursuit explanation](https://www.ri.cmu.edu/pub_files/pub3/coulter_r_craig_1992_1/coulter_r_craig_1992_1.pdf)
* [Coursera lecture](https://www.coursera.org/lecture/intro-self-driving-cars/lesson-2-geometric-lateral-control-pure-pursuit-44N7x)


## Books for Reference
* [Modern Control Engineering](http://sharif.edu/~salarieh/Downloads/Modern%20Control%20Engineering%205th%20Edition.pdf) by Kastukio Ogota.
* [Sliding Mode Control](https://books.google.co.in/books?hl=en&lr=&id=8U1ZDwAAQBAJ&oi=fnd&pg=PP1&dq=sarah+spurgeon+sliding+mode+control&ots=IwTbn51TCr&sig=1jw8ajRiCB2PQLp1iY7kHT6bAsk#v=onepage&q=sarah%20spurgeon%he20sliding%20mode%20control&f=false) by Christopher Edwards and Sarah Spurgeon.
* [Non-Linear and adaptive control](https://books.google.co.in/books/about/Nonlinear_and_Adaptive_Control_Systems.html?id=fygdICP0g0kC&redir_esc=y) by Zhengato Din. (Good explanation of Backstepping).


## Libraries, Tools and Frameworks

* [ROS](https://www.ros.org/)
* [Matlab & Simulink (For Windows)](https://in.mathworks.com/)
* [CasADi](https://web.casadi.org/)
* [Python Control Systems package](https://python-control.readthedocs.io/en/0.8.3/)
* [C++ control toolbox](https://github.com/ethz-adrl/control-toolbox)
* [Drake](https://drake.mit.edu/)
* [OpenAi Gym](http://gym.openai.com/) (Some environments will need to be modified to implement control algorithms)


### Some Interesting Repositories to check out

* [Python - Robotic Algorithms](https://github.com/AtsushiSakai/PythonRobotics)
* [Robotics Planning, Dynamics and Control](https://github.com/YashBansod/Robotics-Planning-Dynamics-and-Control)
* [MATLAB - Trajectory Optimization](https://github.com/MatthewPeterKelly/OptimTraj)
* [TOWR](https://github.com/ethz-adrl/towr) (Trajectory Optimization Library for legged Robots)
