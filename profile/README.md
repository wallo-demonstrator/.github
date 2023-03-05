# WALL-O

WALL-O is an autonomous vehicle that is able to follow lines on the ground and avoid obstacles. This project is carried out as part of the computer science licence at Cergy Paris University.

This project is made by four students :

- [Maxime A](https://github.com/MicheloXy)
- [Alex V](https://github.com/Skodaa)
- [Matthieu V](https://github.com/FalTeaK)
- [Benjamin P](https://github.com/benjaminpmd)

## What is WALL-O?

![WALL-O](https://github.com/wallo-project/.github/blob/main/profile/wallo.png)

WALL-O is a small robot able to track lines and avoid obstacles. The robot can be controlled via a [web application](https://wall-o.benjaminpmd.fr/). In order to use the robot, a server is needed, it will act as a bridge between the robot connection and the web application. The connection between the robot and the server uses a Bluetooth connection.

### How to setup the robot?

The configuration of WALL-O is very simple. A complete guide is available on [this page](https://wall-o.benjaminpmd.fr/docs). You can also find a configuration tutorial on each dedicated repository of the project.

## Organization

The project is divided in three parts. each one have a dedicated repository:

- The script executed by the robot. The code is available [here](https://github.com/wallo-project/robot).
- The server that collect informations from the robot and serve them to the REST API. The code is available [here](https://github.com/wallo-project/server).
- The dashboard that allow the control of the robot and visualization of its parameters in real time. The code is available [here](https://github.com/wallo-project/dashboard).

You can find more informations about each part in their own repository as well as a tutorial on how to configure them.
