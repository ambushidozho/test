cmake_minimum_required(VERSION 3.0.0)
project(123 VERSION 0.1.0)

add_subdirectory(lib/utils)
add_executable(123 src/main.cpp)

target_link_libraries(123 utils)