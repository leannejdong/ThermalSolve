cmake_minimum_required(VERSION 3.22)
project(ThermalSolve)

set(CMAKE_CXX_STANDARD 20)
find_package(Eigen3 3.3 REQUIRED NO_MODULE)

add_executable(ThermalSolve main.cpp)
target_link_libraries(ThermalSolve Eigen3::Eigen)
