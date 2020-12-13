# Robot kinematics and dynamics

#### Courses
* [Introduction to Robotics by Oussama Khatib](https://see.stanford.edu/Course/CS223A): robotics foundations in kinematics, dynamics and control
  + The purpose of this course is to introduce you to basics of modeling, design, planning, and control of robot systems
  + In essence, the material treated in this course is a brief survey of relevant results from geometry, kinematics, statics, dynamics, and control

#### Books for reference
* [A Mathematical Introduction to Robotic Manipulation - Richard M. Murray, CalTech](https://www.cds.caltech.edu/~murray/books/MLS/pdf/mls94-complete.pdf)
* [Robot Dynamics Lecture Notes - Robotic Systems Lab, ETH Zurich](https://ethz.ch/content/dam/ethz/special-interest/mavt/robotics-n-intelligent-systems/rsl-dam/documents/RobotDynamics2017/RD_HS2017script.pdf)
* [Nonlinear dynamics and Chaos by Steven Strogatz](https://g.co/kgs/6azKcp): This is a gem of a book. Not focused on robotic systems but the underlying concepts are universal

# Control Theory
## Classical Control

* [Classical Control Theory](https://www.youtube.com/watch?v=oBc_BHxw78s&list=PLUMWjy5jgHK1NC52DXXrriwihVrYZKqjk) by Brian Douglas.
  **_Why this lecture series? :_**
This collection of videos is intended to supplement a first-year controls class, not replace it. Here the goal will be to take specific concepts in controls and expand on them to provide an intuitive understanding which will ultimately make one a better controls engineer.
Let's take an example of a system that we want to control, say a simple pendulum (the most basic example), suppose we want the pendulum to go upright and stay there, well how do we achieve that? The most basic approach is using the knowledge from control systems to make it stay upright and be able to handle external disturbances for robustness.

* [Control Bootcamp](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR20Mz-VpzgfQs5zrYi085m) by Steve Brunton.
  **_Series info :_** This course provides a rapid overview of optimal control (controllability, observability, LQR, Kalman filter, etc.).  It is not meant to be an exhaustive treatment, but instead provides a high-level overview of some of the main approaches, applied to simple examples in Matlab.
  
**Note:**
For beginners, It is recommended to first go through Brian Douglas (till video 27) course before starting Steve Brunton's course.

* [Control of Mobile Robots](https://www.coursera.org/learn/mobile-robot/home/welcome) by Dr. Magnus Egerstedt.
  **_For whom ?:_** Whoever wants to explore the field of Control Theory, Motion, or path planning should surely have a look at this course to get a basic overview. This course will focus more on differential drive robots.
**_What's good about this course ?:_** It is fairly different from the general long lectured continuous courses, it maintains a very good balance between theory and its implementation. The concepts are explained excellently using some elegant analogies.
**_Course info:_** Course focuses on the problem of establishing control over a robot with the pursuit of making it move safely and optimally. The course covers the classic PID control and its applications in controlling a differential drive robot and then moves on to cover few concepts from the Classical Control Theory which helps span principles and fundamentals applicable for control of almost all types of dynamical systems.

## Advanced
**Note: the focus of these courses is on math and algorithms. You will not study mechanical or electrical design of robots**

* Underactuated Robotics by Russ Tedrake [[textbook](http://underactuated.csail.mit.edu/)] [[videos](https://www.youtube.com/channel/UChfUOAhz7ynELF-s_1LPpWg/playlists)]: Algorithms for Walking, Running, Swimming, Flying, and Manipulation 
  + This course introduces nonlinear dynamics and control of underactuated mechanical systems, with an emphasis on computational methods 
  + Topics include the nonlinear dynamics of robotic manipulators, applied optimal and robust control and motion planning 
  + Discussions include examples from biology and applications to legged locomotion, compliant manipulation, underwater robots, and flying machines
  + Main topics covered Dynamic Programming, LQR, Lyapunov Analysis, Trajectory Optimization, Model Predictive Control, Motion Planning as Search, Pixels to Torques, Robust and Stochastic Control to State Estimation, Reinforcement Learning and few other
* [Advanced Robotics by Peiter Abbeel](https://people.eecs.berkeley.edu/~pabbeel/cs287-fa19/): (optional, only for more conceptual understanding and depth) 
  + Learn the math and algorithms underneath state-of-the-art robotic systems
    - The majority of these techniques are heavily based on optimization and probabilistic reasoning --- both areas with wide applicability in modern Artificial Intelligence. 
    - An intended side-effect of the course is to generally strengthen your expertise in these areas
  + Be able to understand research papers in the field of robotics:
    - Main conferences: ICRA, IROS, RSS, CoRL, ISER, ISRR
    - Main journals: IJRR, T-RO, Autonomous Robots
  + Main topics covered: MDPs, Discretization of Continuous State Space MDPs, Function Approximation / Feature-based Representations, LQR, iterative LQR / Differential Dynamic Programming, Unconstrained Optimization, Constrained Optimization, Optimization-based Control: Collocation, Shooting, MPC, Contact-Invariant Optimization, Motion Planning: RRT, PRM, Trajopt, 3-d poses, Probability Review, Bayes Filters, Multivariate Gaussians, Kalman Filtering, EKF, UKF, Smoother, MAP, Maximum Likelihood, EM, KF parameter estimation, Particle Filters, POMDPs, Imitation Learning, Policy Gradients, Off-policy RL, Model-based RL, Physics simulators working, Sim2Real and few other

## Specific Control Methods

### PID control

* [Understanding PID control](https://www.youtube.com/watch?v=wkfEZmsQqiA&list=PLn8PRpmsu08pQBgjxYFXSsODEF3Jqmm-y) from MATLAB.

### Sliding Mode Control

* [Lecture](https://www.youtube.com/watch?v=v2CNRxG081w&list=PLJmxjP-2T4kthW4VjZn033DYF7Kp_ndt3) by Sarah Spurgeon.
 
### Adaptive Control

* [Non-Linear & Adaptive Control](https://nptel.ac.in/courses/108/102/108102113/) (Nptel) lecture by Dr. Shubendu Bhasin.

### Pure Pursuit controller

* [Pure pursuit explanation](https://www.ri.cmu.edu/pub_files/pub3/coulter_r_craig_1992_1/coulter_r_craig_1992_1.pdf)
* [Coursera lecture](https://www.coursera.org/lecture/intro-self-driving-cars/lesson-2-geometric-lateral-control-pure-pursuit-44N7x)


## Books for Reference

* [Robotics Modeling, Planning, and Controls](https://books.google.co.in/books/about/Robotics.html?id=VsTOQOnQjCAC&printsec=frontcover&source=kp_read_button&redir_esc=y#v=onepage&q&f=false) By Bruno Siciliano, Lorenzo Sciavicco, Luigi Villani, Giuseppe Oriolo. 
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
* [OpenAI Gym](http://gym.openai.com/) (Some environments will need to be modified to implement control algorithms)


### Some Interesting Repositories to check out

* [Python - Robotic Algorithms](https://github.com/AtsushiSakai/PythonRobotics)
* [Robotics Planning, Dynamics and Control](https://github.com/YashBansod/Robotics-Planning-Dynamics-and-Control)
* [MATLAB - Trajectory Optimization](https://github.com/MatthewPeterKelly/OptimTraj)
* [TOWR](https://github.com/ethz-adrl/towr) (Trajectory Optimization Library for legged Robots)
