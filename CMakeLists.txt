cmake_minimum_required(VERSION 3.10)
project(http-beastie)

set(CMAKE_CXX_STANDARD 11)

include_directories(include)

add_executable(http-beastie src/main.cpp src/utils.cpp)