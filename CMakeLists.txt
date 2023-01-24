cmake_minimum_required(VERSION 3.24)
project(arduino)

set(CMAKE_CXX_STANDARD 17)

add_library(arduino library.cpp System.h)
