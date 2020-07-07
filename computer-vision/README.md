# Computer Vision

Extracting information from Images, that help robots “see” and “perceive” as humans do, and understand it’s environment using input from it’s camera. The repository focusses on the traditional aspects of computer vision, particularly multiview geometry. 

## Pre - Requisites

### Linear Algebra
1. [Linear Algebra by Gilbert Strang, MIT OCW](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8) - The course provides a formal introduction to linear algebra. Go through the course patiently because some concepts might seem daunting initially. 
2. [The Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - It provides the motivation and intuition for some of the concepts.

### Digital Image Processing
1. [Image and Video Processing by Guillermo Sapiro, Duke University](https://www.youtube.com/watch?v=bxhJEe38bhY&list=PLZ9qNFMHZ-A79y1StvUUqgyL-O0fZh2rs) - This course is also available on [Coursera](https://www.coursera.org/learn/image-processing). It helps in building the foundation for some concepts that are used along with computer vision techniques, such as using histogram representation, the concept of filters and denoising, thresholding and contours, followed by some of its applications.
2. The above course refers to the text provided by [Digital image processing, Rafael C. Gonzalez](http://web.ipac.caltech.edu/staff/fmasci/home/astro_refs/Digital_Image_Processing_2ndEd.pdf) and one can choose to follow just this book, as it is a standard textbook for Digital Image Processing. 

### Implementation
For the implementation of some of the concepts, [OpenCV](https://opencv.org/releases/) will help you. The documentation not only explains the concepts but also shows how it can be implemented using Python/C++.

## Basic Roadmap

### Introduction to Computer Vision
1. To learn basic concepts that are used in computer vision, [Introduction to Computer Vision by Aaron Bobbick, Georgia Tech](https://www.udacity.com/course/introduction-to-computer-vision--ud810) is a good place to start.
   1. The course first gives a refresher on basic image processing techniques, before introducing camera geometry, such as the pinhole model, intrinsic and extrinsic camera parameters and analysing the point correspondences between two views of the same scene.
   1. The course moves on to introduce the concept of features, scale invariance and then presents the state of the art method, Scale Invariant Feature Transform (SIFT). One can complete the whole course in order to get an idea of different computer vision and image processing techniques.
   1. This will build the foundation for Computer Vision. It also gives sufficient information on Digital Image Processing and the concepts that will be required for the same. If someone watches all the lectures, they are ready to work on a good project in this field. It is recommended that the student is proficient in either MATLAB/Octave or Python. If you are opting for Python, make sure to check out [NumPy](https://numpy.org/) (helpful, but not necessary) and [OpenCV](https://docs.opencv.org/) (for Python. Read up to and including [Image Processing in OpenCV](https://docs.opencv.org/4.1.2/d6/d00/tutorial_py_root.html)), which are the associated libraries that will help you to implement many of the concepts. If one does the first 20% (we encourage anyone who takes this course to watch it till the end) of the course too, then he/she will be able to implement a virtual drawing pad, which requires some basic, but power image processing techniques. As one dives into the concept of features, the student will be able to implement more powerful algorithms that will help in projects such as stitching of two images for making panorama, camera calibration to estimate the focal length of the camera using just the camera feed, removal of distortion from the camera output using mathematical techniques, etc.

2. There is another course, [Computer Vision by Mubarak Shah, University of Central Florida](https://www.youtube.com/playlist?list=PLd3hlSJsX_Imk_BPmB_H3AQjFKZS9XgZm) for the basic concepts of computer vision. The course also has concise lectures on some very famous techniques used such as Lucas Kanade Tracker (KLT), Structure from Motion and Stereo.

3. For the feature detection and matching techniques, one can have a look at the [documentation](https://docs.opencv.org/3.4.2/db/d27/tutorial_py_table_of_contents_feature2d.html) provided by OpenCV. The documentation starts with an introduction to the concept of features, followed by discussing various techniques to obtain the feature points. 

### Books
1. [Computer Vision: Algorithms and Applications, Richard Szeliski](http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf) - This is a standard textbook for Computer Vision. It is recommended to have a strong mathematical base to properly understand some of the sections.  
2. [Multiple View Geometry in computer vision, Richard Hartley and Andrew Zisserman](http://cvrs.whu.edu.cn/downloads/ebooks/Multiple%20View%20Geometry%20in%20Computer%20Vision%20(Second%20Edition).pdf) - This book is specific to multiview geometry. One can refer to this book for more advanced topics.

### Other Lecture Series

For more advanced concepts, one can refer to the following lecture courses selectively.

1. [Computer Vision for Visual Effects by Rich Radke, Rensselaer Polytechnique Institute](https://www.youtube.com/playlist?list=PLuh62Q4Sv7BUJlKlt84HFqSWfW36MDd5a)
2. [Photogrammetry Course by Cyrill Stachniss, University of Bonn](https://www.youtube.com/playlist?list=PLgnQpQtFTOGRsi5vzy9PiQpNWHjq-bKN1)
3. [Multiple View Geometry by Daniel Cremers, Technical University Munich](https://www.youtube.com/playlist?list=PLTBdjV_4f-EJn6udZ34tht9EVIW7lbeo4)

### Lecture Notes

1. [Computer Vision, Carnegie Mellon University](http://www.cs.cmu.edu/~16385/)
2. [Computer Vision Group, TUM Department of Informatics](https://vision.in.tum.de/teaching/ss2020?redirect=1)

### Publications

1. [Distinctive Image Features from Scale-Invariant Keypoints](https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf)
2. [SURF: Speeded Up Robust Features](http://people.ee.ethz.ch/~surf/eccv06.pdf)
3. [A Comparative Evaluation of Well-known Feature Detectors and Descriptors](https://www.researchgate.net/publication/279278472_A_Comparative_Evaluation_of_Well-known_Feature_Detectors_and_Descriptors)
4. [Deep Learning vs. Traditional Computer Vision](https://arxiv.org/pdf/1910.13796.pdf)
5. [Euclidean Reconstruction from Constant Intrinsic Parameters](http://www1.maths.lth.se/matematiklth/vision/publdb/reports/pdf/heyden-astrom-i-96.pdf)

