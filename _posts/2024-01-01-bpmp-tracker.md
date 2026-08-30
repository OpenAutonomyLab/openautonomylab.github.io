---
layout: post
title: "BPMP-Tracker: A Versatile Aerial Target Tracker Using Bernstein Polynomial Motion Primitives"
date: 2024-01-01 00:00:00
categories: research
tags: Target Tracking, Motion Planning and Control, UAV
description: "A fast sample-check-select trajectory planner that chases single or multiple targets through crowded, dynamic environments."
author: "Yunwoo Lee"
published: true
permalink: /bpmp-tracker/
image: /img/posts/bpmp-tracker/placeholder.svg
---

<!-- TODO: swap in a real thumbnail at img/posts/bpmp-tracker/ once available. -->

This letter presents a versatile trajectory planning pipeline for aerial tracking. The proposed tracker is capable of handling various chasing settings such as complex unstructured environments, crowded dynamic obstacles and multiple-target following. Among the entire pipeline, we focus on developing a predictor for future target motion and a chasing trajectory planner. For rapid computation, we employ the sample-check-select strategy: modules sample a set of candidate movements, check multiple constraints, and then select the best trajectory. Also, we leverage the properties of Bernstein polynomials for quick calculations. The prediction module predicts the trajectories of the targets, which do not overlap with static and dynamic obstacles. Then the trajectory planner outputs a trajectory, ensuring various conditions such as occlusion and collision avoidance, the visibility of all targets within a camera image and dynamical limits. We fully test the proposed tracker in simulations and hardware experiments under challenging scenarios, including dual-target following, environments with dozens of dynamic obstacles and complex indoor and outdoor spaces.

Published in *IEEE Robotics and Automation Letters*, 2024.