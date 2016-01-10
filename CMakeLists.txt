project(cppSimple)
cmake_minimum_required(VERSION 2.6)

include_directories(include)

add_executable(cppSimple
  src/main.cpp
  src/operations.cpp
)
