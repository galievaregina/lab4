cmake_minimum_required(VERSION 3.19)
project(C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(
        main.c
        median.c
        median.h)
