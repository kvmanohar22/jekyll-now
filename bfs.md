---
layout: page
title: Breadth First Search
---


<font color="red">2019 Feb 14</font>
Oh, btw it is not the algorithm BFS that one might anticipate but it's my tale of getting into computer vision and robotics.

Back to summers of 2013. I stumbled upon [this talk](https://www.ted.com/talks/sebastian_thrun_google_s_driverless_car/discussion?referrer=playlist-planes_trains_and_automobiles) of Sebastian Thrun talking about Google Self Driving cars. What was most intriguing about this was the way cars could maneuver by building the map of the environment. I could see that the car could detect persons, lane markers, traffic signals, other vehicles etc. That was really really super cool.  That was the moment I decided I wanted to work on self driving cars.

When I started working on computer vision back in 2015-ish, I just picked some interesting problem statements that were closely related to self driving cars namely object detection, segmentation, SLAM, 3D reconstruction and started working on them by reading blogs, books, implementing them etc. It was lot fun working on them. I am now confident to state I have explored these to good depth. What I have lacked however is the breadth. Not that going deeper into a subject hasn't quite payed off in terms of gaining breadth but it's just that it takes considerable depth to come across topics such as compositionality, biological vision and so on. Hence this section on my blog. I will post here the topics along with brief description of them and references for further reading that I feel are going to widen the reach and hence the name of the post BFS.

<font color="red">2019 Feb 19</font>
Recently I came across [this post](https://thegradient.pub/the-limitations-of-visual-deep-learning-and-how-we-might-fix-them/) which outlines the limitations of vision systems using deep learning based approaches and how one could fix them. It was very interesting article for two reasons. One, it not only layed out the dire limitations of the current state-of-the-art computer vision models but it outlined some very interesting ways on how these could be overcome albeit challenging ones. One of the very interesting topic that I later referred to was **compositionality**. I went on to read some of the cited references from the above blog:

- _Compositionality_ by Stuart Geman
- _Hierarchy in Machine and Natural Vision_ by Stuart Geman

In fact, Stuart Geman has papers listed topic wise and it became pretty easy to gather and read them over a weekend. Here are some of the points to take off from the above collection of papers. The papers effectively aim to find the answers for the following questions:
- A child can learn from a single example of a character say **E** and can in effect identify this character in many of its appearances else where. (Although as I write this, there is an inherent debate between `tabula rasa` or whether the biological systems have evolved learning from time immemorial.)
- How do biological systems construct object recognition algorithms with so few examples?

To quote Stuart Geman, "The world is compositional or God exists"!
