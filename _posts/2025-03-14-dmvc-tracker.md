---
layout: post
title: "DMVC-Tracker: Distributed Multi-Agent Trajectory Planning for Target Tracking Using Dynamic Buffered Voronoi and Inter-Visibility Cells"
date: 2025-03-14 00:00:00
categories: research
tags: Planning
description: "A distributed trajectory planner that lets a drone swarm track a moving target without colliding or occluding each other."
author: "Yunwoo Lee"
published: true
permalink: /dmvc-tracker/
image: /img/posts/dmvc-tracker/placeholder.svg
---

<!-- TODO: swap in a real thumbnail at img/posts/dmvc-tracker/ once available. -->

This letter presents a distributed trajectory planning method for multi-agent aerial tracking. The proposed method uses a Dynamic Buffered Voronoi Cell (DBVC) and a Dynamic Inter-Visibility Cell (DIVC) to formulate the distributed trajectory generation. Specifically, the DBVC and the DIVC are time-variant spaces that prevent mutual collisions and occlusions among agents, while enabling them to maintain suitable distances from the moving target. We combine the DBVC and the DIVC with an efficient Bernstein polynomial motion primitive-based tracking generation method, which has been refined into a less conservative approach than in our previous work. The proposed algorithm can compute each agent's trajectory within several milliseconds on an Intel i7 desktop. We validate the tracking performance in challenging scenarios, including environments with dozens of obstacles.

Published in *IEEE Robotics and Automation Letters*, 2025.