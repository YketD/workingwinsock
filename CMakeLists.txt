cmake_minimum_required(VERSION 3.6)
project(untitled)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)


add_executable(untitled ${SOURCE_FILES})
target_link_libraries(untitled ws2_32)