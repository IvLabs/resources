# Computer Vision

Extracting information from Images, that help robots “see” and “perceive” as humans do, and understand it’s environment using input from it’s camera. The repository focusses on the traditional aspects of computer vision, particularly multiview geometry. 


## Prerequisites

### Linear Algebra

1. [Linear Algebra by Gilbert Strang, MIT OCW](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8) - The course provides a formal introduction to linear algebra. Go through the course patiently because some concepts might seem daunting initially. 
2. [The Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - It provides the motivation and intuition for some of the concepts.

### Digital Image Processing

Refer any one of the following courses,

1. [Image and Video Processing by Guillermo Sapiro, Duke University](https://www.youtube.com/watch?v=bxhJEe38bhY&list=PLZ9qNFMHZ-A79y1StvUUqgyL-O0fZh2rs) - This course is also available on [Coursera](https://www.coursera.org/learn/image-processing). It helps in building the foundation for some concepts that are used along with computer vision techniques, such as using histogram representation, the concept of filters and denoising, thresholding and contours, followed by some of its applications.
2. [Digital Image Processing by Prof. Prabir Kumar Biswas, IIT Kharagpur](https://nptel.ac.in/courses/117/105/117105135/) - A comprehensive course on image processing, that deals with all the major topics. Familiarity with linear algebra, probability theory and college calculus is expected.
3. [Introduction to Digital Image Processing by Rich Radke, Rensselaer Polytechnique Institute](https://www.youtube.com/playlist?list=PLuh62Q4Sv7BUf60vkjePfcOQc8sHxmnDX) - This is another comprehensive course, which also talks about some special topics on digital watermarking and digital image forensics.
4. The above set of courses refer to the text provided by [Digital image processing, Rafael C. Gonzalez](http://web.ipac.caltech.edu/staff/fmasci/home/astro_refs/Digital_Image_Processing_2ndEd.pdf). One can choose to follow just this book, as it is a standard textbook for Digital Image Processing.


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


## Books

1. [Computer Vision: Algorithms and Applications, Richard Szeliski](http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf) - This is a standard textbook for Computer Vision. It is recommended to have a strong mathematical base to properly understand some of the sections.
2. [Multiple View Geometry in computer vision, Richard Hartley and Andrew Zisserman](http://cvrs.whu.edu.cn/downloads/ebooks/Multiple%20View%20Geometry%20in%20Computer%20Vision%20(Second%20Edition).pdf) - This book is specific to multi view geometry. One can refer to this book for more advanced topics.
3. [Computer Vision - A Modern Approach, David Forsyth and Jean Ponce](https://eclass.teicrete.gr/modules/document/file.php/TM152/Books/Computer%20Vision%20-%20A%20Modern%20Approach%20-%20D.%20Forsyth,%20J.%20Ponce.pdf) - Another book, that also talks about image processing and specific computer vision problems such as tracking, stereo problem, structure from motion, etc.
4. [Computer Vision for Visual Effects](https://cvfxbook.com/) - Apart from standard topics, it covers some special topics on image matting, motion capture and 3D data acquisition. Applications are centred around visual effects, used frequently in the movies and television industry.


## Other Lecture Series

For more advanced concepts, one can refer to the following lecture courses selectively.

1. [Computer Vision for Visual Effects by Rich Radke, Rensselaer Polytechnique Institute](https://www.youtube.com/playlist?list=PLuh62Q4Sv7BUJlKlt84HFqSWfW36MDd5a)
2. [Photogrammetry Course by Cyrill Stachniss, University of Bonn](https://www.youtube.com/playlist?list=PLgnQpQtFTOGRsi5vzy9PiQpNWHjq-bKN1)
3. [Photogrammetric Computer Vision by Cyrill Stachniss, University of Bonn](https://www.youtube.com/playlist?list=PLgnQpQtFTOGTPQhKBOGgjTgX-mzpsOGOX) (A concise version for the course above)
3. [Multiple View Geometry by Daniel Cremers, Technical University Munich](https://www.youtube.com/playlist?list=PLTBdjV_4f-EJn6udZ34tht9EVIW7lbeo4)


## Lecture Notes

1. [Computer Vision, Carnegie Mellon University](http://www.cs.cmu.edu/~16385/)
2. [Computer Vision Group, TUM Department of Informatics](https://vision.in.tum.de/teaching/ss2020?redirect=1)
3. [Computer Vision, University of Washington](https://courses.cs.washington.edu/courses/cse455/12wi/)
4. [Computer Vision, RWTH Aachen University](http://www.vision.rwth-aachen.de/course/11/)


## Publications

It consists of a list of publications, survey papers and tutorials for some concepts that are usually covered in lectures and books.

1. [A Flexible New Technique for Camera Calibration](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr98-71.pdf)
2. [An Efficient Solution to the Five - Point Relative Pose Problem](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.86.8769&rep=rep1&type=pdf)
3. [Determining the Epipolar Geometry and its Uncertainty: A Review](https://www.cs.auckland.ac.nz/courses/compsci773s1c/resources/IJCV-Review.pdf)
4. [Triangulation](https://users.cecs.anu.edu.au/~hartley/Papers/triangulation/triangulation.pdf)
5. [A Review of Solutions for Perspective - n - Point Problem in Camera Pose Estimation](https://www.researchgate.net/publication/328036802_A_Review_of_Solutions_for_Perspective-n-Point_Problem_in_Camera_Pose_Estimation)
6. [Euclidean Reconstruction from Constant Intrinsic Parameters](http://www1.maths.lth.se/matematiklth/vision/publdb/reports/pdf/heyden-astrom-i-96.pdf)
7. [Self - Calibration and Metric Reconstruction Inspite of Varying and Unknown Intrinsic Camera Parameters](https://www.researchgate.net/profile/Marc_Pollefeys/publication/225241106_Self-Calibration_and_Metric_Reconstruction_Inspite_of_Varying_and_Unknown_Intrinsic_Camera_Parameters/links/53f5cc320cf2fceacc6f6e3d.pdf)
8. [Bundle Adjustment - A Modern Synthesis](https://lear.inrialpes.fr/pubs/2000/TMHF00/Triggs-va99.pdf)
9. [A Survey on Structure from Motion](https://arxiv.org/pdf/1701.08493.pdf)
10. [Structure - from - Motion Revisited](https://openaccess.thecvf.com/content_cvpr_2016/papers/Schonberger_Structure-From-Motion_Revisited_CVPR_2016_paper.pdf)
11. [Multi - View Stereo: A Tutorial](https://carlos-hernandez.org/papers/fnt_mvs_2015.pdf)
12. [Image Matching from Handcrafted to Deep Features: A Survey](https://link.springer.com/article/10.1007/s11263-020-01359-2)

