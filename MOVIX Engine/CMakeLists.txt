cmake_minimum_required(VERSION 3.16)

project("MOVIX Engine")

add_library(mvxengine main.cpp log.h)

install (TARGETS mvxengine DESTINATION "${CMAKE_SOURCE_DIR}/build")