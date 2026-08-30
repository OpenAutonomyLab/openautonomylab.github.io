---
layout: post
title: "Multirobot Collaborative Monocular SLAM Utilizing Rendezvous"
date: 2021-03-19 00:00:00
categories: research
tags: SLAM
description: "A collaborative monocular SLAM system that fuses maps across robots by exploiting rendezvous events, camera-only."
author: "Yunwoo Lee"
published: true
permalink: /collaborative-slam-rendezvous/
image: /img/posts/collaborative-slam-rendezvous/thumbnail.gif
---

<!-- TODO: this description is paraphrased, not the verbatim published abstract
     (IEEE Xplore's full text was not accessible while drafting this post) —
     swap in the official abstract once available. -->

Multi-robot teams can build a shared map faster than any single robot, but fusing each robot's map usually calls for extra sensing to register them against one another. This work proposes a collaborative monocular SLAM system, including a map-fusion algorithm, that instead exploits rendezvous — moments when two team members come within view of each other during normal operation — using only a monocular camera on each robot, with no additional sensors required.

Received the 27th Samsung Human-Tech Paper Award (Silver Prize). Published in *IEEE Transactions on Robotics*, 2021.