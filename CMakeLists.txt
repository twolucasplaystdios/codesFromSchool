cmake_minimum_required(VERSION 3.15)
project(HomeworkTool VERSION 1.0.0 LANGUAGES CXX)

find_package(Python3 REQUIRED COMPONENTS Development)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)


add_executable(run_hw "src/main.cpp")

target_include_directories(MyApp PRIVATE ${Python3_INCLUDE_DIRS})
target_link_libraries(MyApp PRIVATE Python3::Python)