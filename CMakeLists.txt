cmake_minimum_required(VERSION 3.21)
project(my_lab3)

set(CMAKE_CXX_STANDARD 14)

include_directories(Laba3_ocean)

add_executable(my_lab3
        Laba3_ocean/Laba3_ocean.cpp
        Laba3_ocean/ocean.cpp
        Laba3_ocean/ocean.h)
