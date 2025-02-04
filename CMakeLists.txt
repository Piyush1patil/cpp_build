# Specify the minimum version of CMake required
cmake_minimum_required(VERSION 3.10)
# Define the project name
project(HelloProject)
# Set the C++ standard to use
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
# Add the executable target
add_executable(hello hello.cpp)
