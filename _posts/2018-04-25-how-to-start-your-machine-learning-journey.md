---
title: 'How to start your Machine Learning journey in 6 easy steps'
date: 2018-04-25
permalink: /posts/2018/04/how-to-start-your-machine-learning-journey/
tags:
  - machine learning
  - deep learning
  - convolutional neural networks
  - how to start machine learning
---


![](https://zdnet2.cbsistatic.com/hub/i/r/2018/04/13/cf38d399-bca4-48f1-9161-bbfa9cea167a/resize/370xauto/671e316ba2a27b98148f1bb6fbb88cf3/deep-learning-pix.png)

How to start your Machine Learning journey in 6 easy steps
=====

As a complete new student to this great field called Machine Learning, I did struggle to find my way into linear regressions, convolutions and so forth when I first started my AI journey. Although I belonged to (and still do) a Machine Learning group inside a Computer Vision laboratory, I had no help at all to start. My advisers suggested to start reading papers about Machine Learning, but I did not find it helpful at all, specially starting from scratch. However, there are many ways for people with or without Computer Science or Math knowledge to join the field, at least to try it out and to see what it is possible. In this article I will share some incredible resources that helped me to become aware of the power of AI and to start producing some interesting programs.

The first thing to understand is that, currently, Machine Learning (ML) is heavily dependent upon data. Most things and services you use today they collect your data in form of clicks, images, text and voice, so they can improve their ML programs. That is why Facebook and Google for example are free. And the most part of the revenue they generate is with, of course, advertisement. Things you like or look for on the web are saved into their database so these companies can suggest links and products that you will likely consume based on your behavior and the behavior of people similar to you. But how do they do that?

In order to explain that let's start from the beginning. One of the subfields of Machine Learning is Deep Learning, which is a form of supervised learning. This term corresponds to a computer programmed to learn something from zero, making predictions and being corrected by humans or data. Let's say a robot starts learning the differences between cats and dogs, both animals which are quite similar if you compare them to insects, for example. The robot will see a cat and say that it is a dog, then we, amazing teachers for robots, will say no, it is a cat. The robot will save it into its memory, be sad about it and look at the next animal in line, a dog. The robot will say it is a dog and we will say yes, then the robot will be happy about it and to the next on the line it goes. For every right prediction, the robot becomes happier with their guess. For every bad prediction, it becomes sad because it made the wrong guess, but the form of a cat or dog in their memory will become clearer, since it is slowly starting to understand different features, such as shape, size, color and many others. You can say the robot is like a toddler learning how to differentiate animals in their early ages. Even us, adults have difficulties telling animals apart. For instance, is a fox a canine or feline? Is a tortoise a reptile or amphibian?

![](https://www.telegraph.co.uk/content/dam/news/2017/01/25/JS114779665_wwwAlamycom_Cats-and-Dogs_trans_NvBQzQNjv4Bqn2n2hk5qKEJ--A9z8HbLAhS03i2pzHkxg356GvlPLeE.jpg?imwidth=450)

But how is the dog-cat example related to the question of the advertisements? It is the machine learning approach. The methods are very different but the basics are the same: the robot analyzes data and make predictions, which can be telling a dog or cat apart or suggesting which shoes are you most likely to buy in your news feed. There are so many amazing examples of Machine Learning products and research that it is difficult to show them all in this article, but I will say a few that are very common: speech recognition, object classification, health related problems such as finding malignant tumors, [teaching robots to play Mario](https://www.youtube.com/watch?v=qv6UVOQ0F44) and much more. But for that we need to understand about concepts such linear algebra, statistics, probability and calculus.

Now let's finally go to the tasty resources I talked about in the beginning of the article. I will provide the most useful links in my Machine Learning journey that is still far from the end. I will divide it into 6 steps that I think are crucial for a good understanding of the whole Machine Learning spectrum.

### Step 1: Basic understanding and motivation

Here are videos that I find interesting to demonstrate the power of Machine Learning and to get you started on some concepts and jargons.

* [Deep Learning SIMPLIFIED](https://www.youtube.com/watch?v=b99UVkWzYTQ) is a series of videos that explains briefly, for people outside the Computer Science field, what is Deep Learning and how it works.
* [Siraj Raval's Intro to Deep Learning](https://www.youtube.com/watch?v=vOppzHpvTiQ) has lots of memes and it is easy to follow.

### Step 2: Going deep with neural networks

Here I mention the videos that I think are a must for people who really want to start learning the field.

* [3BLue1Brown's But what is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk) is in my opinion the best and easiest neural network lecture out there. Many examples and you can really see the network alive! Please watch the whole series of 3 chapters and one appendix of backpropagation.
* [Andrej Karpathy's Standford Neural Networks Course](https://www.youtube.com/watch?v=NfnWJUyUJYU). It was published just two years ago and it is already outdated, but still very good to understand how Convolutional Neural Networks work.

### Step 3: Going back to the intro of Machine Learning itself

I left it for the third step on purpose. Since Machine Learning is a lot of math, nothing better than to get introduced to the field by its amazing methods and products and then going back to understand the real deal. Of course I am talking about [Andrew Ng's Machine Learning course](https://www.coursera.org/learn/machine-learning) on Coursera.

### Step 4: Getting your hands dirty

Since now you are aware of the basics and the middle of Machine Learning, it is time for you to install and run some frameworks with different types of data. There are many available out there, but I will list just a few.

* Caffe is a framework for image classification. It has two versions: [Caffe](http://caffe.berkeleyvision.org/) and [Caffe2](https://caffe2.ai/). Don't worry which version you try, both have good support and work pretty well.
* [Faster R-CNN](https://github.com/rbgirshick/py-faster-rcnn) is a framework for object detection based on Caffe. It is outdated but I believe it easier to install and run than the current [Detectron](https://github.com/facebookresearch/Detectron). But be free to try both.
* [YOLO](https://pjreddie.com/darknet/yolo/) is also for object detection but it is faster than Faster R-CNN.

### Step 5: Building your own nets

This is a broad step, but for any case you should of course know how to work with one of the most common libraries/frameworks: Torch, Tensorflow or Keras. This is the step I am currently in so I can only talk about the online course I am taking: Kadenze's [Creative Applications of Deep Learning with TensorFlow](https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow-iv). It is not the greatest course out there but it is free and it does make you to program some TensorFlow on your own. Complete all the assignments and be free to move to the next step!

### Step 6: Reading Papers and understanding the state-of-the-art methods

For researchers and workers on the competitive market out there this is the most important step and (un)fortunately ad infinitum, since almost every week a new research is published or a new product comes out. This repository on Github has the most cited papers from 2012 to 2016 and it is a great start, but we are on a two years gap right now. Two of the ways I use to keep myself up to date with everything coming out is: the Machine Learning subreddit and Siraj Raval's Youtube channel. If you have any other useful resource please share in the comments section!

---------------------------------------------------------------------------------

The article finally came to an end! By no means I wanted to give all the resources available, but just the ones I used and found the most useful. There are still much more to be released and I am really excited for the future of Machine Learning! I hope you enjoyed it and if you have any comments or questions feel free to contact me.

Cheers!
