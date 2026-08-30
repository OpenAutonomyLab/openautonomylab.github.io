---
layout: post
title: "Autonomous Aerial Dual-Target Following Among Obstacles"
date: 2021-01-01 00:00:00
categories: research
tags: Target Tracking, Motion Planning and Control, UAV
description: "A visibility-aware planner that lets a single drone follow two targets at once amid obstacles."
author: "Yunwoo Lee"
published: true
permalink: /aerial-dual-target-following/
image: /img/posts/aerial-dual-target-following/placeholder.svg
---

<!-- TODO: this description is paraphrased, not the verbatim published abstract
     (IEEE Xplore's full text was not accessible while drafting this post) —
     swap in the official abstract, and a real thumbnail at
     img/posts/aerial-dual-target-following/, once available. -->

Following more than one target with a single chaser drone is challenged by visibility issues that a single-target setup does not face: inter-target occlusion and a limited field of view, on top of the usual risk of occlusion and collision with obstacles. This work builds a visibility score field for two targets that accounts for the field-of-view limit and inter-target occlusion, together with a fast sweeping algorithm to compute that field in real time. A hierarchical planning pipeline then uses the field to generate a chasing motion, and the full system is demonstrated on a real drone following two targets among obstacles.

Published in *IEEE Access*, 2021.