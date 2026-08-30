---
layout: post
title: "Mono-Camera-Only Target Chasing for a Drone in a Dense Environment by Cross-Modal Learning"
date: 2024-05-30 00:00:00
categories: research
tags: Planning, Learning
description: "Chasing a target with a single RGB camera by learning a cross-modal representation that stands in for multi-sensor data."
author: "Yunwoo Lee"
published: true
permalink: /mono-camera-chasing/
image: /img/posts/mono-camera-chasing/placeholder.svg
---

<!-- TODO: swap in a real thumbnail at img/posts/mono-camera-chasing/ once available. -->

Chasing a dynamic target in a dense environment is one of the challenging applications of autonomous drones. The task requires multi-modal data, such as RGB and depth, to accomplish safe and robust maneuver. However, using different types of modalities can be difficult due to the limited capacity of drones in aspects of hardware complexity and sensor cost. Our framework resolves such restrictions in the target chasing task by using only a monocular camera instead of multiple sensor inputs. From an RGB input, the perception module can extract a cross-modal representation containing information from multiple data modalities. To learn cross-modal representations at training time, we employ variational autoencoder (VAE) structures and the joint objective function across heterogeneous data. Subsequently, using latent vectors acquired from the pre-trained perception module, the planning module generates a proper next-time-step waypoint by imitation learning of the expert, which performs a numerical optimization using the privileged RGB-D data. Furthermore, the planning module considers temporal information of the target to improve tracking performance through consecutive cross-modal representations. Ultimately, we demonstrate the effectiveness of our framework through the reconstruction results of the perception module, the target chasing performance of the planning module, and the zero-shot sim-to-real deployment of a drone.

Published in *IEEE Robotics and Automation Letters*, 2024.