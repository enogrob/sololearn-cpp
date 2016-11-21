cmake_minimum_required(VERSION 3.4)
project(sololearn_cpp)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES src/main.cpp)
add_executable(sololearn_cpp ${SOURCE_FILES})
add_executable(main src/main.cpp)