---
title: "Getting Started"
categories:
  - tutorials
  - primer
description: "A 2018 take on an introduction to deep vision, reinforcement learning and NLP; an age when cross domain boundaries are fast dissolving."
header:
  teaser: https://www.nvidia.com/content/dam/en-zz/Solutions/research/research-home-areas-computer-vision-407-ud@2X.jpg
tags:
  - tutorials
  - primer
  - references

toc: true
toc_label: "Contents"
toc_icon: "gear"
---

We are in 2018, a year where computer vision seems more dominated by Deep Learning and Reinforcement learning than photogrammetry, and when  language is the next big barrier to be crossed. Where does one then start on understanding each domain and their cross-linking? With a bit of fooling around in these topics, we attempt to piece out a slightly coherent path.

How one goes about this is still quite conflicting- for instance a lot skip classical computer vision (processing and filter based) and get away with neural nets for pattern recognition. We are open to suggestions in the path advised, so feel free to drop in your comments below.

{% include figure image_path="https://i.ytimg.com/vi/aBVXfqumTXc/maxresdefault.jpg" alt="LSD Slam" caption="Credits: LSD SLAM Foodcourt dataset" %}

For those who would like a really extensive list of references, we have a compiled list in our content repository, similar to an _Awesome Deep Vision_ initiative. This can be found [here](https://github.com/iitmcvg/Content), under the _References_ folder.

Here are some references to get started with Computer Vision, Deep Learning and AI in general:

## Computer Vision:

### Courses
* The udacity course [ud810]() is a MOOC version of the Georgia Tech course : CS4495. You can find the 2015 run [here](https://www.cc.gatech.edu/~afb/classes/CS4495-Spring2015-OMS/) and the 2017 run [here](https://www.cc.gatech.edu/~hays/compvision/). The 2015 run was taken primarily by Aaron Bobbick, while the 2017 counterpart by [James Hays](https://www.cc.gatech.edu/~hays/).

Both run closely follow the Szeliski book, so you might find it easier to refer to this.

* MIT's computer vision course: this is available on [youtube](https://www.youtube.com/watch?v=CLOAswsxudo).

* UCF CRCV's 2012 course taken by Mubarak Shah is also a solid MOOC. You can find it [here](https://youtu.be/715uLCHt4jE).

### References

* [Computer Vision:  Models, Learning, and Inference](http://www.computervisionmodels.com/) - Simon J. D. Prince 2012. Quite a standard including Rick's book.
* [Computer Vision: Theory and Application](http://szeliski.org/Book/) - Rick Szeliski 2010. Could be your primary reference if you happen to follow the udacity course.
* [Computer Vision: A Modern Approach (2nd edition)](http://www.amazon.com/Computer-Vision-Modern-Approach-2nd/dp/013608592X/ref=dp_ob_title_bk) - David Forsyth and Jean Ponce 2011. Slightly more rigourous in terms of the signal processing.
* [Multiple View Geometry in Computer Vision](http://www.robots.ox.ac.uk/~vgg/hzbook/) - Richard Hartley and Andrew Zisserman 2004. This is nearly the gold standard of reference for geometry based computer vision (epipolar, stereo and perspective).

### Libraries

1. OpenCV remains the single biggest library for open-source implementations with both python and Cpp.
2. Scikit (and scipy) are very useful when considering signal processing techniques as well as non-standard implementations (general Hough transforms,..etc).
3. PCL: Point Cloud Library, primarily written in Cpp, with a few python bindings around. The library is widely used, however not many updates have been issued since 2014. You can find strawlab's python bindings for PCL [here](https://github.com/strawlab/python-pcl).


A more exhaustive list (of resources) for computer vision is hosted on our repository, [here](https://github.com/iitmcvg/Content/blob/master/References/awesome_CV.md).

### Sample Code

We have included jupyter notebooks for most computer vision techniques under our [Content](https://github.com/iitmcvg/Content) repository. This is a work in progress, so do feel free to hit up a pull request for certain notebooks.

## Machine Learning

### Courses
### References
### Libraries
### Sample Code

## Deep Learning

### Courses
### References
### Libraries
### Sample Code

## Reinforcement Learning

### Courses
### References
### Libraries
### Sample Code

## Natural Language Processing (and Generation)
### Courses
### References
### Libraries
### Sample Code

Do share this post if you find it helpful.
