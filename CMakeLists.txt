cmake_minimum_required(VERSION 3.12)
project(MyProject VERSION 1.0.0)
add_executable(roadtesting main.cpp
                           Map.cpp
                           Map.h
                           Lane.cpp
                           Lane.h
                           Road.cpp
                           Road.h)