# Robotics Challenges
Some simple robotics challenges to play around with.

---

Working day to day with robotics (specifically, legged robots) yields many challenges which are both fun and interesting to solve.
This repo is an attempt to reproduce some interesting challenges in a synthetic environment and allow anyone to attempt them.
Often newcomers will feel overwhelmed by the amount and breadth of knowledge required in robotics and even if they are really
passionate about a certain problem the learning curve to setting up a reasonable simulation environment for them to then build on
is sharp. I wanted to try remove this learning curve and provide a base robotic platform that people can use to explore, learn and
invent in.

The idea is to initially aim this at undergraduate students in STEM programmes that are considering robotics as a career or are
looking for robotics internships. I want to provide some fun challenges that they can use to get a feel for the field and hopefully
use when applying for internships or entry-level jobs. In this spirit the challenges are going to be short and focus mainly on the
user finding and implementing a solution through some simple functions/methods in a framework so that they don't haveto worry about
designing or architecting what can be fairly complex software.

As time goes I hope to expand it to a wider audience and offer a wider array of challenges 

The challenges currently include:
1. Create a real-time visualisation tool for some common data streams:
    * Robot state (position, orientation, velocity)
    * Motor states (angle, velocity, current, voltage, temperature)
    * Onboard sensor payloads (cameras, Lidar, etc)
2. Create a vision system for the robot for improved navigation:
    * Location of obstacles relative to the robot.
    * Classification of obstacles into those the robot can go over/through and those it must avoid.
    * Characterisation of permissible obstacles to allow the robot to adapt to them.

