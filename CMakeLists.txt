cmake_minimum_required(VERSION 3.0)
project(example)

include(cmake/ide.cmake)
include(cmake/platform.cmake)

add_executable(example WIN32 src/main.c)
