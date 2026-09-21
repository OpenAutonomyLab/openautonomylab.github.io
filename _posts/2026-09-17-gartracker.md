---
layout: post
title: "GAR-Tracker: Target-Visible Trajectory Planning for a Ground Assistant Robot"
date: 2026-09-17 00:00:00
categories: research highlights
tags: Planning
description: "A trajectory planner for target following with a wheeled robot, tackling nonholonomic constraints under a limited field of view."
author: "Yunwoo Lee"
published: true
permalink: /gar-tracker/
image: /img/posts/gar-tracker/thumbnail.gif
---

The target tracking from a motion-planning perspective has been consistently studied with drones, owing to their agility and ease of control, particularly because position and yaw control can be decoupled. However, in indoor environments, the use of drones is often restricted due to safety and noise concerns, motivating the need for tracking autonomy with ground robots. To this end, this paper proposes a planning framework for wheeled robots equipped with a limited field-of-view camera, without the aid of a gimbal, that tackles the challenge of nonholonomic constraints. We propose a Bernstein polynomial motion primitive (BPMP)-based sample–check–select approach for differential-drive robots that handle both unstructured and dynamic obstacle scenarios effectively. Unlike previous BPMP-based works, our method explicitly accounts for the effect of the trajectory on the heading direction and its impact on tracking performance, enabling effective tracking under nonholonomic constraints. Moreover, to achieve a high tracking success rate, we alleviate the conservativeness in existing BPMP-based methods. Finally, we demonstrate applicability in diverse real-world environments and further validate its effectiveness even in challenging scenarios with dozens of dynamic obstacles in confined spaces.

Published in *IEEE Access*, 2026.
