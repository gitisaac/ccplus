# Set the minimum CMake version required
cmake_minimum_required(VERSION 3.10)

# Project name and C++ standard
project(CCPlus VERSION 0.1.0)

# Set the C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Include directories (header files)
include_directories(include)

# Add the executable by listing the source files
add_executable(ccplus
    src/main.cpp
)
