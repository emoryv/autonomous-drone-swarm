# Autonomous Drone Swarm

**Cornell Autonomous Drone Project Team (CUAD) · Software Developer · September 2025–present**

A case study of my software contributions to a four-drone autonomous swarm competing in the International Aerial Robotics Competition.

## My contributions

- Developed and flight-tested **ROS 2 perception, planning, and multi-agent coordination software**.
- Integrated visual odometry, camera-based obstacle avoidance, and **D* Lite replanning on a Raspberry Pi 5** for GPS-denied flight.
- Trained and deployed a **PyTorch gesture classifier** using MediaPipe hand landmarks and temporal smoothing.
- Connected gesture recognition to swarm arming, takeoff, and landing commands through **MAVROS**.

## System components

| Area | Project approach |
| --- | --- |
| Navigation without GPS | Visual odometry |
| Obstacle awareness | Camera-based obstacle avoidance |
| Replanning | D* Lite |
| Onboard compute | Raspberry Pi 5 |
| Autonomy software | ROS 2 perception, planning, and coordination |
| Operator interaction | MediaPipe landmarks, PyTorch classification, temporal smoothing |
| Flight-command integration | MAVROS |

## Gesture-control subsystem

The gesture classifier is part of the swarm project: hand landmarks provide input to the classifier, temporal smoothing stabilizes its output, and the resulting recognized gestures are translated into flight commands through MAVROS. This work connects an ML model to the behavior of a physical multi-drone system.

## Validation

My work included flight testing alongside software development. This write-up does not assert a measured classification accuracy, flight-success rate, or competition placement because those results are not included in the published project summary.

## Repository scope

This is a portfolio case study of collaborative Cornell CUAD work. It does not contain the original team source code, flight data, or model weights. The four-drone system is a team project; the contributions above describe my role.

**Technologies:** Python, ROS 2, Raspberry Pi 5, D* Lite, visual odometry, PyTorch, MediaPipe, MAVROS

[Back to my profile](https://github.com/emoryv)
