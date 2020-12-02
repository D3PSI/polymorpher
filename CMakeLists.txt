cmake_minimum_required(VERSION 2.8 FATAL_ERROR)
cmake_policy(VERSION 2.8)

set(NAME POLYMORPHER)

project(${NAME})

set(CMAKE_BUILD_TYPE "Release")

add_executable(polymorpher polymorpher.c)
