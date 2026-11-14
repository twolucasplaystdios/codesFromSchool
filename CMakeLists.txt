cmake_minimum_required(VERSION 3.10)
project(Homework)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(include)


add_library(logger "src/logger.cpp")
target_include_directories(logger PUBLIC "src/headers")


add_executable(menu "src/main.cpp")