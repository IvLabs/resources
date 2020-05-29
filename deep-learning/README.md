# Deep Learning Resources

## Roadmap to Deep Learning for Visual Recognition
1. Before jumping to learning-based techniques for vision, it is recommended to go through some of the fundamental concepts of Computer Vision. From our experience, we found [Introduction to Computer Vision](https://www.udacity.com/course/introduction-to-computer-vision--ud810) is a good starting point, and it covers some concepts like Image as function, filtering, convolution, etc. You can do this course upto *Lesson 4: Linearity and Convolution* before moving to DL. This builds a strong mathematical foundation about images and helps you to easily grasp DL later. You will understand about CNNs much easily after doing this course
2. Once you get a hang on computer vision concepts, it is advisable to go through some of the linear algebra concepts as well. Some of them include eigendecomposition, single value decomposition, matrix and vector norms (and other imp concepts. Refer [Deep Learning by Ian Goodfellow, Yoshua Bengio and Aaron Courville](https://www.deeplearningbook.org/) textbook for more references)
3. Python programming language will be used in most of the courses. If you dont know python then go through some tutorials like [this one by Corey Schafer](https://www.youtube.com/watch?v=YYXdXT2l-Gg&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU).
4. Now, you are ready to start with the [Deep Learning Specialization by Andrew Ng](https://www.coursera.org/specializations/deep-learning). The foundation built through these courses are very essential. Make proper notes during the course.
5. Code your artificial neural networks and convolutional neural networks from scratch using numpy. These maybe covered within the course itself, so be sure to complete the course assignments with proper understanding.
6. You should now pickup a framework to work with. Most members of IvLabs prefer PyTorch. In case you have an inclination towards industry, TensorFlow is the way to go, whereas for research, you should go for PyTorch.
7. You can skip the *Sequence Modelling course of Deep Learning Specialization* and do it later if you are interested in Natural Language Processing (NLP) or signal processing.
8. Keep yourself updated with latest reasearch papers. Reddit and Twitter are highly recommended for this purpose.
9. Ask for support from seniors who have already worked on these fields.

**NOTE for futher studies:** 
- If one's focus is to use deep learning for object detection, segmentation (feature level understanding) etc, then understanding only Image Processing is sufficient. [Digital image processing by Rafael C. Gonzalez](http://web.ipac.caltech.edu/staff/fmasci/home/astro_refs/Digital_Image_Processing_2ndEd.pdf) is a standard book to refer.
- If one's focusing on deep learning for Computer Vision/Perception application then Image Processing and complete course on [Introduction to Computer Vision](https://www.udacity.com/course/introduction-to-computer-vision--ud810) is requisite. Perception includes concepts of 3D perspective, Stereo, Optical flow, object tracking, visual recognition etc which are all very important. In simple words, Image Processing is kinematics and Computer Vision is dynamics. Book on [Computer Vision:
Algorithms and Applications by Richard Szeliski](http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf) is a very good book for reference and focuses more towards mathematical approaches.

## Courses
In these courses, you will learn the foundations of Deep Learning, understand how to build neural networks, and learn how to undertake Deep Learning projects systematically.

#### General Courses on Deep Learning
1. [Deep Learning Specialization by Andrew Ng](https://www.coursera.org/specializations/deep-learning)
2. [Deep Learning - IIT-Madras CS7015](https://www.cse.iitm.ac.in/~miteshk/CS7015.html)
3. [Deep Learning - Stanford CS230](https://cs230.stanford.edu/)
4. [Fast.ai](https://course.fast.ai/)

#### Machine Learning
1. [Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)
2. [Machine Learning - Stanford CS229](http://cs229.stanford.edu/)
3. [Fast.ai - Machine Learning](http://course18.fast.ai/ml)

#### Vision
1. [Introduction to Computer Vision](https://www.udacity.com/course/introduction-to-computer-vision--ud810)
2. [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/)

#### Natural Language Processing 
1. [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)
2. [Fast.ai - NLP](https://www.fast.ai/2019/07/08/fastai-nlp/)

## Course Reviews
[Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)
The Deep Learning Specialization, presented by Andrew Ng, is a collection of five courses, each offering a good requiem of required concepts and implementations for almost all kinds of basic deep learning. The contents and goals of each of the courses are further explained below.
   1. [Neural Networks and Deep Learning](https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning) aims at explaining the basics of neural networks and deep learning, starting from very basic problems like linear and logistic regression. It helps one understand and actually implement neural networks and basic optimization algorithms from scratch, mainly in NumPy. Using an analogy, this course actually teaches you to bake from scratch including how to use an oven.
   2. [Improving Deep Neural Networks](https://www.coursera.org/learn/deep-neural-network?specialization=deep-learning) focuses more on improving the performance of neural networks by employing efficient optimization and normalization algorithms. If the first course is a course that teaches you baking, then this one teaches you how and where to use which ingredient to get the best results. However, the last few assignments are based on TensorFlow.
   3. [Structuring Machine Learning Projects](https://www.coursera.org/learn/machine-learning-projects?specialization=deep-learning) is a course that helps one develop an intuition as to which architectures and optimization algorithms would work best for a given machine learning problem. Further, it also covers the basics of transfer learning and multi-task learning. It is a course oriented more towards industrial and result oriented practices. So, this is a course that teaches you to industrialize your bakery.
   4. [Convolutional Neural Networks](https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning) brings to the table, the most fundamental and powerful tools used in almost all kinds of deep learning problems that are coupled with image processing or even signal processing at times. The course covers all the basics and is almost a must for anyone planning to work with images and deep learning. The assignments are in NumPy and TensorFlow. So this course teaches you how to bake a cake because who doesn’t like cake.
   5. [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models) is a course that explains recurrent neural networks and other architectures and techniques used in applying deep learning on sequential data. It focuses more on Natural Language Processing and audio signal processing which is a completely different and rather nascent domain of deep learning. The assignments use NumPy. This is like learning to bake pizzas.

A healthy approach, containing a good mix of results and fairly decent understanding would be to first complete the first two courses, then study the fourth one along with a bit of Image Processing and Computer vision followed by a small project using NumPy, from scratch, followed by an introductory project like [The Digit Classifier](http://www.ivlabs.in/mnist.html) using either PyTorch or TensorFlow.

The fifth course can be a bit heavy if done before implementing a project or two using Image Processing and Deep Learning even though it deals with a very different paradigm. The third course, however, holds little potential with respect to research-oriented learning

## Books
1. [Deep Learning by Ian Goodfellow, Yoshua Bengio and Aaron Courville](https://www.deeplearningbook.org/)
2. [Digital image processing by Rafael C. Gonzalez](http://web.ipac.caltech.edu/staff/fmasci/home/astro_refs/Digital_Image_Processing_2ndEd.pdf)
3. [Computer Vision: Algorithms and Applications by Richard Szeliski](http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf)

## Blog Posts/Tutorials
1. [Lilian Weng](https://lilianweng.github.io/lil-log/)

## Framework Tutorials
1. TensorFlow
   - [TensorFlow in Practice Specialization](https://www.coursera.org/specializations/tensorflow-in-practice)
   - [sentdex TensorFlow/Keras playlist](https://www.youtube.com/playlist?list=PLQVvvaa0QuDfhTox0AjmQ6tvTgMBZBEXN)
2. PyTorch
   - [PyTorch Official Tutorials](https://pytorch.org/tutorials/)
   - [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
   - [Sentdex PyTorch playlist](https://www.youtube.com/playlist?list=PLQVvvaa0QuDdeMyHEYc0gxFpYwHY2Qfdh)
