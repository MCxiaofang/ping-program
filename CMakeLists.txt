cmake_minimum_required(VERSION 3.19)
project(myping C)

set(CMAKE_C_STANDARD 99)
include_directories(ping.h)
add_executable(myping ping.c)