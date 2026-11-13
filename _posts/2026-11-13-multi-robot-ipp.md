---
layout: post
title: "Multi-Robot Learning-Based Informative Path Planning Using Spatio-Temporal Gaussian Process Kalman Filter"
date: 2026-11-13 00:00:00
categories: research
tags: Planning, Learning
description: "A decentralized multi-robot informative path planning framework that fuses footprint-level camera measurements with a grid-based spatio-temporal Gaussian Process-Kalman filter for persistent target monitoring."
author: "Yunwoo Lee"
published: true
permalink: /multi-robot-ipp/
image: /img/posts/multi-robot-ipp/thumbnail.gif
---

Multi-robot informative path planning (IPP) for persistent target monitoring requires robots to reason about spatial uncertainty, temporal evolution, and practical sensing and communication constraints. Recent learning-based multi-robot IPP methods use Gaussian Processes (GPs) for target uncertainty, but often rely on simplified sensing models and centralized belief updates. We propose a grid-based spatio-temporal GP-Kalman filtering framework for learning-based multi-robot IPP. Instead of maintaining one GP per target, we represent anonymous target presence as a single latent field over a discrete workspace grid. The proposed recursive update assimilates footprint-level camera measurements and supports arbitrary fields of view and range-dependent noise. A GP-derived temporal process update inflates uncertainty over time to account for moving targets. For decentralized deployment, each robot maintains its own mapper and exchanges fixed-size belief summaries rather than raw measurements. Received beliefs are fused using diagonal covariance intersection to remain conservative under unknown inter-robot correlations. We integrate the mapper with a reinforcement-learning policy for graph-based neighbor selection. In simulation, the centralized deployment improves target visitation and attains about 20% lower posterior target uncertainty than learning-based and classical auction/coverage baselines, a large share of which stems from the belief representation itself. A real-world two-UAV experiment demonstrates transfer to outdoor multi-robot search over a large field (>7000 m^2).

Published in *IEEE Robotics and Automation Letters*, 2026.
