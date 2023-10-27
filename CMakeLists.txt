cmake_minimum_required(VERSION 3.16)
project(UUID)

set(CMAKE_CXX_STANDARD 11)

link_libraries(uuid)

add_executable(example example.cpp)
