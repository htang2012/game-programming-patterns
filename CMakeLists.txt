cmake_minimum_required(VERSION 3.0)
project(MyProject)

# Set C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add all source files in ./code directory
set (SOURCES 
     code/cpp/main.cpp
     )
# Add executable target
add_executable(gamerun ${SOURCES})
