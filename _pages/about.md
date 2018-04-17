---
permalink: /
title: "A little bit about me"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Bio
-----
I am a second year graduate student at [Keio University](http://www.keio.ac.jp). I am currently studying about deep learning and computer vision under the supervision of [Professor Hideo Saito](http://hvrl.ics.keio.ac.jp/saito/). I have a bachelor degree in Computer Science by the Federal University of Parana (UFPR), in Brazil. My graduation thesis was "Development of Web Platform for Child Learning", a web system designed in Ruby on Rails to assist physically challenged children to learn reading and writing.

I am passionate about teaching, nature, deep learning and helping people in need through science. I speak native Portuguese, English and Japanese, and I have learned both foreign languages by myself, playing games, watching TV shows, listening to music and chatting with friends.


Current Research
-----
I have been working with deep learning to build a new framework capable of providing robots waiters the ability to understand when cups and glasses are empty so they can take the containers away or offer new drinks to customers.  

The framework is based on two different convolutional neural networks: region proposal conv nets and normal conv nets, using Faster R-CNN and Caffe. The first net is responsible for finding the cup in the frame, while the second one will attach what we call 'states' to the cups: either a cup has liquid (Liquid) inside or it is empty (Empty). However, when the container is opaque and the angle does not help, we cannot say it is either one of the previous two states, so we introduce a new state for this specific case (Unknown).

![](https://paulomarcos.github.io/images/fullmethod.png)

>The implementation scheme. The input received is resized and sent through the first convolutional neural network. Then, the cups are identified and cropped and sent through the second network, which is responsible for classifying into one of the three states. The last step is the output of the framework, which contains the labels for each cup with the corresponding state in relation to the existence or the lack of liquid.

We use new labels for common images of cups and glasses provided by ImageNet and also build our own dataset, called Keio Cup Dataset (KCD), which contains over 1100 images of cups and glasses to improve the classification accuracy on objects that are known within the limitations of the cafe or restaurant. We show an example of the images of KCD below:

![](https://paulomarcos.github.io/images/kcd.png)

So far, we have achieved an accuracy of over 0.88 when using our test set for the KCD.

The framework is still under development and will be released on Github when it is finished.


Awards & Experience
-----

I have been granted two full scholarships to study abroad. The first one is a one-year study abroad program called [Science Without Borders](www.cienciasemfronteiras.gov.br/web/csf-eng), which I had the amazing experience of studying two terms at [University of Victoria](https://uvic.ca) and one term for a co-op program working as a software developer at [CanAssist](https://canassist.ca), where I developed and implemented from the ground up an accessible [Single Switch Movie Player](http://www.canassist.ca/EN/main/programs/technologies-and-devices/hobbies-and-leisure/single-switch-movie-player.html) for individuals with severe cognitive and physical disabilities.
The second scholarship was granted by [Ministry of Education, Culture, Sports, Science and Technology: MEXT](http://www.mext.go.jp/en/) of Japan. I am currently enrolled as a MEXT student at Keio University where I will finish my Masters program in March 2019.


Timeline
------
**2017-2018**: Master student at Keio University by MEXT Scholarship  
**2016**: Research student at Keio University by MEXT Scholarship  
**2013-2014**: Study abroad + Coop Program at University of Victoria by Science Without Borders Scholarship  
**2011-2015**: Bachelor in Computer Science at Federal University of Parana  


Other Projects
-----
On a side I micro vlog my experience in Japan for my family and friends in Brazil and I teach English for Japanese customers at [Lancul](https://lancul.com), an English Conversation Cafe in Tokyo.

I was founder and president of the University Clubs Association in 2015. I was responsible to introduce the culture of University Clubs, so far inexistent in Brazil, in my University, as seen in this [video](https://www.youtube.com/watch?v=1NmZZpbuq_g) (with English subtitles).

I have created two trailers for games without any knowledge of filming. The first was created by me and my cousin for fun during a summer vacation project: [Team Fortress 2: War Movie Trailer](https://www.youtube.com/watch?v=YxhDKlNwBoA). The second was made for a game development course at the University of Victoria: [Call of Ireland - Potatic Justice](https://www.youtube.com/watch?v=U_wRHXVEsuY). I was also responsible for creating the website for it which can still be accessed through [this link](http://web.uvic.ca/~pmdj/callofireland/).
