# State Estimation and Localization, SLAM

Use noisy inputs from multiple sensors, to estimate, as accurately as possible, the current location of the robot within its environment, and also, in some cases, build a map of its surroundings as it explores the area.

## Prerequisites

Basic Knowledge about Probability, Jacobians, Linear Algebra and Numpy in python.


## Course is fit for

This field being a part of Probabilistic Robotics is fit for people who are interested in the planning, mobile robotics, software aspect of robotics and developing autonomous robots. Navigation is one of the most challenging competencies required of a mobile robot. Success in navigation requires success at the four building blocks of navigation:

**Perception:** the robot must interpret its sensors to extract meaningful data.

**Localization:** the robot must determine its position in the environment.

**Cognition**- the robot must decide how to act to achieve its goals.

**Motion Control:** the robot must modulate its motor outputs to achieve the desired trajectory. Localization is a recently developed field of robotics which finds its application in *self-driving cars, unmanned aerial vehicles, autonomous underwater vehicles, planetary rovers*, newer domestic robots and even inside the human body. Localization involves estimating the position of a robot with respect to the surroundings. Knowing the robot’s location as an essential precursor in making decisions about future actions.

This concept is critical if you wish to develop any autonomous robot. However this field involves good knowledge of mathematics. This concept can be further extended to what is known as **Simultaneous Localization and Mapping (SLAM)** which involves building a map of the surroundings while localizing the robot in that particular surrounding. Localization algorithms are used in **navigation** and **mapping** and **odometry of virtual reality or augmented reality**


## Overview

***Note:** The following references are good just to get an overview of the concept along with visual understanding. They may not cover all the mathematical details about the concept.*

* [How a Kalman filter works](https://www.bzarg.com/p/how-a-kalman-filter-works-in-pictures/)
* [Student Dave's Tutorials](http://studentdavestutorials.weebly.com/)
* [Overview of localization](http://www.cs.cmu.edu/~rasc/Download/AMRobots5.pdf)


## Courses

* [Introduction to Mobile Robotics](http://ais.informatik.uni-freiburg.de/teaching/ss19/robotics/) by Dr. Wolfram Burgard.
 The course provided by Dr. Wolfram Burgard is good for understanding the underlying math behind the probabilistic algorithms used in state estimation and localization. The course can be taken as an introduction to the various concepts in the field of mobile robotics.

* [SLAM-Course](https://www.youtube.com/watch?v=U6vr3iNrwRA&list=PLgnQpQtFTOGQrZ4O5QzbIHgl3b1JHimN_) by Cyrill Stachniss.

* [State Estimation and Localization for Self-Driving Cars](https://www.coursera.org/learn/state-estimation-localization-self-driving-cars/home/welcome)
In these courses you will learn about the basic concepts of different types of motion models of a mobile robot, some basic concepts regarding probability and Euclidean geometry. Further these courses cover various probabilistic state estimation algorithms such as Kalman Filters, Extended Kalman Filters and Unscented Kalman Filters which work on the Prediction-Correction Cycle. This course is specifically crafted for understanding the various methodologies used for localization, sensor fusion, sensor selection, etc. in self-driving cars. It may not cover all the concepts of localization used in robotics, but is targeted for an audience specifically interested in self-driving cars.

* [Mobile Sensing and Robotics II](https://www.ipb.uni-bonn.de/msr2-2020/) by Cyrill Stachniss.
This is an advanced course based on Simultaneous Localization and Mapping. It covers the concepts of graph based SLAM algorithms as well as 
Visual SLAM. In the second part of the course some fundamental concepts of Point Clouds are addressed. Other topics include System Calibration, Sensor Synchronization and SfM application. 

* [Nonlinear State Estimation for Robotics and Computer Vision](http://wavelab.uwaterloo.ca/indexe9a5.html?page_id=533)

## Books and research papers for Reference

* [Optimal State Estimation: Kalman, H∞, and Nonlinear Approaches](https://onlinelibrary.wiley.com/doi/book/10.1002/0470045345) by Dan Simon.

* [Circumventing dynamic modeling: evaluation of the error-state Kalman filter applied to mobile robot localization](https://ieeexplore.ieee.org/document/772597)

* [The Unscented Kalman Filter for Nonlinear Estimation](https://www.seas.harvard.edu/courses/cs281/papers/unscented.pdf)

* [Unscented Kalman Filter Tutorial](https://www.cse.sc.edu/~terejanu/files/tutorialUKF.pdf) 

* [Advanced Vehicle State Estimation: A Tutorial and Comparative Study](https://www.sciencedirect.com/science/article/pii/S2405896317323674)

* [Quaternion kinematics for the error-state Kalman filter](https://arxiv.org/pdf/1711.02508.pdf) (Advanced Reading)

* [Madgwick's paper on sensor fusion](https://x-io.co.uk/res/doc/madgwick_internal_report.pdf)
