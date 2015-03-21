cmake_minimum_required(VERSION 3.1)
project(GCJ)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    ReverseWords/src/main.c)

add_executable(GCJ ${SOURCE_FILES})