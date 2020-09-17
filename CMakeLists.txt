cmake_minimum_required(VERSION 3.11)
project(Wampus_World)

set(CMAKE_CXX_STANDARD 14)

add_executable(Wampus_World check_true_false.cpp)
target_link_libraries(Wampus_World ${DEPENDENCIES})
