cmake_minimum_required(VERSION 3.4)
project(pybind_vid)
add_subdirectory(pybind11)
pybind11_add_module(hog features.cpp)
