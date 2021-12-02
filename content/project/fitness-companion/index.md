---
title: Gym Companion
subtitle: An automatic gym exercise counting system using surveillance cameras
date: 2017-07-20T01:26:22.780Z
summary: "**Gym Companion** helps you track the workouts in the gym
  automatically without using any wearables."
draft: false
featured: false
tags:
  - prototype
links:
  - url: https://www.youtube.com/watch?v=TuxIsRUnF30
    name: Demo
    icon_pack: fab
    icon: youtube
  - url: https://drive.google.com/file/d/0ByDUwWJTuexwRjBoYUh3a1hSN2dCUFhDdmxlcjZMb1FyR1Y0/view?usp=sharing&resourcekey=0-G635WwTLRnXvnZbtoTCJDw
    name: Report
    icon_pack: fab
    icon: drive
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
**Gym Companion** uses surveillance cameras installed at the gym to help people track their workouts automatically. It consists of several subsystems as follows:

* **Tracking People:** Gym count utilizes existing deep learning-based human detection models to track the people in the gym.
* **Exercise Recognition**: It uses a machine learning model using sparse Spatio-temporal features to recognize the type of exercise. As a proof of concept, the current model is trained to recognize four exercises i.e. squats, dumbbell, running on a treadmill, and using an elliptical machine.
* **Exercise Counting**: As most of the gym exercises are periodic, so this problem reduces down to counting the number of repetitions in periodic motion. We built upon the existing research works using deep convolutional networks for counting repetitions in periodic motion. For non-periodic exercises such as running on a treadmill, we record the time duration.