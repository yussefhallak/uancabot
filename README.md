# UancaBot

**An autonomous mobile robot for field robotics, built at the GARRA Robotics Lab, UFSM.**

UancaBot is a ROS 2 mobile robot platform for work in real environments, like driving along crop rows the way a phenotyping robot does. It is built to move on its own, and to work naturally with the people around it.

## What it does

- **Drives autonomously** along planned routes, with its position tracked from its wheels in real time.
- **Understands spoken commands** in Portuguese, fully offline, so it works in the field with no internet.
- **Can be driven by hand** with a joystick over Wi-Fi when someone needs to take over.
- **Stays safe**: an emergency stop, speed limits and a stop command that always wins.
- **Runs onboard**: everything runs on the robot's own computer, packaged so it starts the same way every time.

## My work

I work across the whole robot: the hardware and electronics, motor control, the robot software, and the interfaces that let people command it by voice and by hand.

## Built with

ROS 2, Linux, Docker, Python, C++, ESP32 and Arduino, with offline speech recognition.

## What's next

Autonomous field missions, perception, and richer interaction between the robot and the people who work with it.

## About

UancaBot is developed at the GARRA Robotics Lab (Automation and Applied Robotics Group), Universidade Federal de Santa Maria. Page by Yussef Omar Hallak, undergraduate research fellow.

The source code is private. Reviewers and hiring teams can request access at yussefomarh@gmail.com.
