cmake_minimum_required(VERSION 3.3)
project(cJSON)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    cJSON.c test.c)

add_executable(cJSON ${SOURCE_FILES})