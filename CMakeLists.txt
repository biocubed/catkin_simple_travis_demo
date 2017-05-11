cmake_minimum_required(VERSION 2.8.3)

project(catkin_simple_travis_demo)

find_package(catkin_simple REQUIRED)

catkin_simple()

cs_add_executable(talker src/talker.cpp)
cs_add_executable(listener src/listener.cpp)

cs_install()

cs_export()