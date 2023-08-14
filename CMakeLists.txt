cmake_minimum_required(VERSION 3.22.0)
project(Homework_Testing)
add_executable(Homework_Testing main.cpp)

add_subdirectory(Catch2)

target_link_libraries(Homework_Testing PRIVATE Catch2::Catch2)