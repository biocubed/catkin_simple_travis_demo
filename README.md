# catkin_simple_travis_demo
 [![Build Status](https://travis-ci.org/biocubed/catkin_simple_travis_demo.svg?branch=master)](https://travis-ci.org/biocubed/catkin_simple_travis_demo)

This repository contains files which demonstrate how to include both catkin_simple and .travis-ci support for a github project.
The source code is copied from ROS's publisher subscriber demo.
The following files are used to make this build work.

1. dependencies.rosinstall: This file points the rospack program to the catkin_simple package hosted on github.

2. .travis.yml: This file contains the instructions for initializing the Virtual Machine (VM) used to test compile.

Note that this is a minimal example. Both of the above files can be modified as necessary to include additional dependencies.