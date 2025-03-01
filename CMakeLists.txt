cmake_minimum_required(VERSION 3.10)
project(cpp-adaptive-radix-tree)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add executable
add_executable(main src/main.cpp)

# Include directories
target_include_directories(main PRIVATE ${CMAKE_SOURCE_DIR}/src)
