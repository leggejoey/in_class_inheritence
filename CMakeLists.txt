cmake_minimum_required(VERSION 3.28)
project(in_class_inheritence)

set(CMAKE_CXX_STANDARD 17)

add_executable(in_class_inheritence main.cpp
        rectangle.cpp
        rectangle.h
        square.cpp
        square.h
        point.cpp
        point.h)
